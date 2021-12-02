<script>
	import '/static/global.css';
	import Header from '../components/Header.svelte';
	import Footer from '../components/Footer.svelte';
	import CoverImage from '../components/CoverImage.svelte';
</script>

<Header />
<CoverImage />
<main>
	<slot />
</main>

<Footer />
