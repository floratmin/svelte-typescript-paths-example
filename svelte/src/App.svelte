<script lang="ts">
	import { stringFunctions } from './scripts';
	import { test } from '@foo/scripts/index';
	export let name: string;
</script>

<main>
	<h1>Hello {stringFunctions.double(name)}!</h1>
	<h1>Hello {test.id(name)}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
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