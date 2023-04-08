<div class="center">
	<h1>Michiru so coooooooool</h1>
	<h1 class="uwu">:3</h1>
</div>
<div class="furryfeet">
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img src="/1.png" alt="Michiru image" />
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img src="/2.png" alt="Michiru image" />
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img src="/3.png" alt="Michiru image" />
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img src="/4.png" alt="Michiru image" />
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img src="/5.png" alt="Michiru image" />
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img src="/6.png" alt="Michiru image" />
	<!-- svelte-ignore a11y-img-redundant-alt -->
	<img src="/7.png" alt="Michiru image" />
</div>
<div class="backgwound" />

<style>
	.backgwound {
		background-color: #000000;
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		opacity: 0.5;
		z-index: 0;
	}
	:global(body) {
		font-family: Arial, Helvetica, sans-serif;
		background-image: url('/background.webp');
		background-size: cover;
		/* background-repeat: no-repeat; */
		background-position: center;
		margin: 0;
		padding: 0;
	}

	h1 {
		color: white;
		z-index: 1;
	}

	.uwu {
		color: white;
		font-size: 10rem;
		margin-bottom: 0;
		z-index: 1;
	}

	.center {
		display: flex;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		margin: 0;
		padding: 0;
	}

	.furryfeet {
		position: absolute;
		bottom: 0;
		left: 0;
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: 100%;
		flex-wrap: wrap;
		margin: 0;
		padding: 0;
		z-index: 1;
	}

	.furryfeet img {
		margin: 0;
		padding: 0;
		position: relative;
		bottom: 0;
		width: 12%;
		height: 12%;
		align-self: flex-end;
	}
</style>
