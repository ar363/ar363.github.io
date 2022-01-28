<div class="container">
	<div class="hero">
		<p class="hero__intro">Hi, I'm Aditya</p>
		<h1 class="hero__title">I make websites</h1>
	</div>
</div>

<style>
	.hero {
		height: 80vh;
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: center;
	}

	.hero__intro {
		font-size: 1.25rem;
		font-weight: 400;
		margin: 0;
		margin-bottom: 1.5rem;
		padding-left: 2px;
		color: var(--fg);
	}

	.hero__title {
		font-size: 6rem;
		font-weight: 500;
		margin: 0;
		color: var(--fg);
		line-height: 1;
	}

	@media screen and (max-width: 640px) {
		.hero__title {
			font-size: 4rem;
		}
	}
</style>
