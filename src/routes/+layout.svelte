<script>
	import './styles.css';
</script>

<div class="app">
	<main>
		<slot />
	</main>

	<footer>
		<p style="font-weight: 100">© 2024 <a href="https://github.com/paakkis">paakkunainen</a></p>
	</footer>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Roboto+Mono:ital,wght@0,100..700;1,100..700&display=swap');

	.app {
		display: flex;
		font-family: "Roboto Mono", monospace;
		flex-direction: column;
		min-height: 100vh;
		background-image: url(../lib/images/juusot3.png);
		background-size: cover;
		background-repeat: no-repeat;
		
	}

	main {
		flex: 1;
		display: flex;
		flex-direction: column;
		padding: 1rem;
		width: 100%;
		max-width: 64rem;
		margin: 0 auto;
		box-sizing: border-box;
	}

	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
		background-color: var(--color-footer);
	}

	footer a {
		font-weight: bold;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
