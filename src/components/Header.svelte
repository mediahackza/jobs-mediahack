<script>
	let headerImage
</script>

<div class="header">
	<div class="header-scheme">
		<div class="header-logo"><a href="https://mediahack.co.za">Media Hack</a></div>
		<div class="menu">
			<div class="menu-item">
				<a href="https://mediahack.co.za/what-we-do/" target="_blank">What we do</a>
			</div>
			<div class="menu-item">
				<a href="https://mediahack.co.za/the-team/" target="_blank">The Team</a>
			</div>
			<div class="menu-item">
				<a href="https://mediahack.co.za/category/work/" target="_blank">Our Work</a>
			</div>
			<div class="menu-item">
				<a href="https://jobs.mediahack.co.za" target="_blank">Jobs</a>
			</div>
		</div>
	</div>
</div>

<style>
	.header {
		width: 100%;
	}
	.header-logo {
		font-family: 'Roboto', Arial, Helvetica, sans-serif;
		font-weight: 700;
		font-size: 1.5rem;
	}
	.header-scheme {
		padding: 15px 30px;
		display: grid;
		grid-template-columns: 1fr 5fr;

		background: #000;
		color: #fff;
	}
	.menu * {
		display: inline-block;
	}
	.menu a {
		color: #fff;
		text-decoration: none;
	}
	.menu a:hover {
		color: rgb(120, 194, 223);
	}
	.menu-item {
		padding: 10px 20px 0px;
		text-transform: uppercase;
		font-weight: 700;
		font-size: 0.9rem;
	}
	.header-logo a {
		color: #fff;
		text-decoration: none;
	}
</style>
