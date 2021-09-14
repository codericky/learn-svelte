<script lang="ts">
	export let name: string;
</script>

<main>
	<h1>Hello my name, is {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">website new using svelte</p>
	<p>Visit the <a href="https://rickynoviansyah.netlify.app">Personal website</a> about me</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>