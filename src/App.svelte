<script lang="ts">
	import Header from "./components/Header.svelte";
	import Banner from "./components/Banner.svelte";
	export let name: string;
</script>

<main>
	<Header />
	<Banner/>
</main>

<style>
	main {
		text-align: center;
		/* max-width: 240px; */
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