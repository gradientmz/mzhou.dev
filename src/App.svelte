<svelte:head>
	<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Inter&display=swap" rel="stylesheet">
	<script src="https://kit.fontawesome.com/c1ee2ceba9.js" crossorigin="anonymous"></script>
</svelte:head>

<script>
</script>

<style>
	body {
		font-family: 'Inter', sans-serif;
		overflow-x: hidden;
	}
	.heading {
		display: flex;
		align-items: center;
		justify-content: center;
		flex-direction: column;
		overflow: hidden;
		padding: 1rem;
		background: linear-gradient(0deg, #00000088 30%, #ffffff44 100%), url("https://images.unsplash.com/photo-1538970272646-f61fabb3a8a2?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1241&q=80");
		background-size: cover;
    background-repeat: no-repeat;
    background-position: center center;
		height: 30rem;
	}
	.projects {
		padding: 1.5rem 0rem;
		background-color: #151f2e;
		padding-bottom: 2.5rem;
	}
	.title {
		color: white;
		margin: 0;
		text-align: center;
		font-size: 4rem;
	}
	.subtitle {
		color: white;
		margin: 0;
		text-align: center;
	}
	.projects-title {
		padding: 0rem 2rem;
		color: white;
		overflow: hidden;
	}
	.project-item {
		border: 1px solid gray;
		margin: 0.5rem 2rem;
		background-color: #141921;
		color: white;
		transition: 0.2s;
		overflow: hidden;
	}
	.project-item:hover {
		transform: scale(1.04);
		box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
	}
	.project-item-title {
		margin: 1rem 1rem 0.5rem 1rem;
	}
	.project-item-description {
		margin: 0rem 1rem 1rem 1rem;
		font-weight: normal;
	}
	.text {
		background-color: whitesmoke;
		padding: 1.5rem 0rem;
	}
	.text-title {
		padding: 0rem 2rem;
	}
	.text-description {
		padding: 0rem 2rem;
		font-weight: normal;
	}
	.introduction { background-color: whitesmoke; }
	.footer { background-color: #54beff; }
	.media-container {
		margin-top: 2rem;
	}
	.media {
		color: white;
		margin: 0.5rem;
		transition: 0.2s;
	}
	.media:hover {
		color: gray;
	}
	a {
		text-decoration: none;
	}
</style>

<body>
<div class="heading">
	<h1 class="title">mzhou.dev</h1>
	<h3 class="subtitle">A middle schooler</h3>
	<ul class="media-container">
		<a class="media" href="https://github.com/gradientmz"><i class="fab fa-github-alt fa-2x"></i></a>
		<a class="media" href="https://twitter.com/gradientapps"><i class="fab fa-twitter fa-2x"></i></a>
		<a class="media" href="mailto:xinyunzhouu@gmail.com"><i class="fas fa-at fa-2x"></i></a>
	</ul>
</div>
<div class="text introduction">
	<h2 class="text-title">Hello! My name is Mark.</h2>
	<h3 class="text-description">I'm currently in 8th grade, and I enjoy running, sometimes cooking, and of course programming!<br><br>I started learning web development a while ago, and am having a lot of fun with it so far. This site is actually built with Svelte, which is a pretty new framework right now.</h3>
</div>
	<div class="projects">
		<h2 class="projects-title">Some of my projects:</h2>
		<div>
			<a href="https://windchill.mzhou.dev/">
			<div class="project-item">
				<h2 class="project-item-title">Windchill</h2>
				<h3 class="project-item-description">Calculates how cold it feels outside, accounting for wind!</h3>
			</div>
				</a>
		</div>
		<a href="https://haste.mzhou.dev/">
		<div class="project-item">
				<h2 class="project-item-title">Haste</h2>
				<h3 class="project-item-description">A simple typing practice site with thousands of quotes and lots of small features!</h3>
			</div>
			</a>
		
		<a href="https://dicepass.mzhou.dev/">
		<div class="project-item">
				<h2 class="project-item-title">Dicepass</h2>
				<h3 class="project-item-description">Generates super-secure diceware passwords!</h3>
			</div>
			</a>
		
		<a href="https://bluetable.mzhou.dev/">
		<div class="project-item">
				<h2 class="project-item-title">Bluetable</h2>
				<h3 class="project-item-description">A periodic table practice site I made in a day!</h3>
			</div>
			</a>
	</div>
	<div class="text footer">
	<h2 class="text-title">Thanks for reading!</h2>
	<h3 class="text-description">The site is pretty short right now, but more content will be added in the future.</h3>
</div>
	</body>