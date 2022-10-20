<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>
<script>
	let a = 1;
	let b = 2;
</script>
<div>
	<input type="number" bind:value={a}>
	<input type="number" bind:value={b}>
	<p>{a} + {b} = {a + b}</p>	
</div>
<style>
	div {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		width: 100vw;
		height: 50vh;
		overflow: none;
	}
</style>
