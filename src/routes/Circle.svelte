<script>
	export let imageUrl = '';
	export let url = '';
</script>

<a href={url}>
	<div class="circle">
		<img height="32" width="32" src={imageUrl} alt="Logo"/>
	</div>
</a>


<style>
	.circle {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 3rem;
		height: 3rem;
		border: 1px solid var(--color-socials);
		border-radius: 50%;

	}

	.circle:hover {
		border-color: var(--color-theme-1); /* Change border color to green on hover */
		box-shadow: 0 0 8px var(--color-theme-1); /* Glowing effect with a green shadow */
	}
</style>