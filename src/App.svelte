<script lang="ts">
	export let name: string;
</script>

<main>
	<header class="App-header">
		<a href="https://high-end.fathym-it.com/"><img src="./assets/T-logo-grey.jpg" class="pf-logo" alt="home" /></a>
		<div class="siteNav">
			<a href="https://high-end.fathym-it.com/brand/">
				<button class="navbutton">Brand</button>
			</a>
			<a href="https://high-end.fathym-it.com/dashboard/">
				<button class="navbutton">Dashboard</button>
			</a>
			<a href="https://high-end.fathym-it.com/digital/">
				<button class="navbutton">Digital</button>
			</a>
		</div>
	</header>
	<br>
	<div class="dashboard">
		<iframe title="athlete - Page 1" class="responsive-iframe" src="https://app.powerbi.com/view?r=eyJrIjoiMjk0ZTQ4YWEtNjliNy00ZWIwLThkYmUtYjEzOWE1YmJkYmZhIiwidCI6IjZkY2JlYmQwLWY4ZDAtNGE5ZC04OWU1LTU4NzNlODE0NmIwYSIsImMiOjR9" frameborder="0"></iframe>
	</div>
	<br>
	<div class="builtin">
		Built in Svelte<br>
		<img src="./assets/svelte2.jpg" class="frameworkImage" alt="Svelte" />
	</div>
</main>

<style>	
	.App-header {
		background-color: #fff;
	}

	.siteNav {
		float: right;
		padding: 2rem;
	}

	.navbutton {
		background-color: #5a5a5a;
		border: none;
		color: white;
		padding: 15px 32px;
		text-align: center;
		text-decoration: none;
		display: inline-block;
		font-size: 16px;
		margin: 4px 10px;
		cursor: pointer;
	}

	.pf-logo {
		width: 96px;
		height: auto;
		padding: 1rem 0 2rem 4rem;
	}

	@media only screen and (max-width: 650px) {		
		.navbutton {
			padding: 7px 16px;
			margin: 2px 5px;
		}

		.pf-logo {
			width: 96px;
			height: auto;
			padding: 1rem 0 1rem 1rem;
		}
	}

	.dashboard {
		text-align: center;
		margin: 0 auto;
		position: relative;
		overflow: hidden;
		width: 100%;
		padding-top: 56.25%;
	}
		
	.builtin {
		margin: 0 auto;
		text-align: center;
		font-family: Verdana, Geneva, Tahoma, sans-serif;
		font-size: 14px;
		font-weight: bold;
		padding:2rem;
		background-color: white;
		width: 200px;
	}

	.frameworkImage {
		padding-top:1rem;
		height: 100px;
	}

	.responsive-iframe {
		position: absolute;
		top: 0;
		left: 0;
		bottom: 0;
		right: 0;
		width: 100%;
		height: 100%;
	}
</style>