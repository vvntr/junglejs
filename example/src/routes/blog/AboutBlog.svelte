<script>
	import Nav from "../../components/Nav.svelte";
</script>

<Nav page="/blog/about-blog"/>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
    }
    
	ul {
		margin: 0 0 1em 0;
		line-height: 1.5;
    }

</style>

<svelte:head>
	<title>Blog</title>
</svelte:head>

<main>
    <h1>About the Blog</h1>

    <p>Trying to write awesome stuff here!</p>
</main>