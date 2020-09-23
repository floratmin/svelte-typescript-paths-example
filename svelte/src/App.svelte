<script lang="ts">
	import { other } from '@foo/scripts';
	import { double } from '@foo/scripts/test';
	import { more } from '@foo/scripts/more';
	export let name: string;
</script>

<main>
	<h1>Hello {other.reverse(name)}!</h1>
	<h1>Hello {double(name)}!</h1>
	<h1>Hello {more.newer(name)}</h1>
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