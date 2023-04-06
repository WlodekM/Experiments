<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>My new svelteKit app!</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>Hello and welcome to my site!</h1>
	<a href="/about">About my site</a>
	<a href="/blog">My blog</a>
</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}
</style>
