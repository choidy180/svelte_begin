<script>
	import './styles.css';
</script>

<div class="app">
	<main>
		<slot />
	</main>
	<footer>
	</footer>
</div>

<style>
	.app {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}
	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
