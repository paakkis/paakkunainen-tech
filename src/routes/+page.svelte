<script>
	import Circle from './Circle.svelte';
</script>

<svelte:head>
	<title>Juuso Paakkunainen</title>
	<meta name="description" content="A data person" />
</svelte:head>

<section>
	<div class="card">
		<div class="name">
			<h1 style="margin: 0; font-weight: 400; letter-spacing: -.1rem;">Juuso Paakkunainen</h1>
		</div>
		<div class="title">
			<h2 style="margin-bottom: 1rem; font-weight: 300;">A data person</h2>
		</div>
		
		<div class="socials">
			<Circle imageUrl="https://cdn.simpleicons.org/github/181717" url="https://github.com/paakkis"/>
			<Circle imageUrl="https://cdn.simpleicons.org/linkedin/181717" url="https://www.linkedin.com/in/juusopaakkunainen/"/>
			<Circle imageUrl="https://cdn.simpleicons.org/untappd/181717" url="https://untappd.com/user/paakkis"/>
			<Circle imageUrl="https://cdn.simpleicons.org/faceit/181717" url="https://www.faceit.com/en/players/zouse-"/>
		
		</div>
		
	</div>


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


	.socials {
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
		gap: .5rem;

	}

	.card {
		background-color: var(--color-theme-2);
		padding: 1rem;
		display: flex;
		flex-direction: column;
		border-radius: .5rem;
		-webkit-box-shadow: 2px 9px 80px -14px rgba(0,0,0,0.75);
		-moz-box-shadow: 2px 9px 80px -14px rgba(0,0,0,0.75);
		box-shadow: 2px 9px 80px -14px rgba(0,0,0,0.75);
		border: 1px solid var(--color-socials);
	}

	.name {
		display: flex;
	}

	.title {
	
	}


	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
