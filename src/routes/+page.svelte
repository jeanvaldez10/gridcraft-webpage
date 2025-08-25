<script>
	import Header from "$lib/components/Header.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import HeroGrid from "$lib/components/hero-grid/HeroGrid.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
	<title>GridCraft: A Powerful SvelteKit Data Grid Solution</title>
	<link rel="canonical" href="https://grid_craft.vercel.app"> 

	<meta name="description" content="Empower your projects with GridCraft, the comprehensive data grid library designed for developers. Streamline data management, enhance user experience, and unleash the full potential of your applications. Get started now!">
	<meta name="keywords" content="GridCraft, SvelteKit, data grid, data management, data visualization, data analysis, customizable grid, efficient grid, powerful grid, JavaScript grid library, dynamic data grid">
	<meta name="author" content="gridcraft">
	<meta property="og:title" content="GridCraft: A Powerful SvelteKit Data Grid Solution">
	<meta property="og:description" content="Empower your projects with GridCraft, the comprehensive data grid library designed for developers. Streamline data management, enhance user experience, and unleash the full potential of your applications. Get started now!">
	<meta property="og:image" content="https://grid_craft.vercel.app/webpage.jpg">
	<meta property="og:url" content="https://grid_craft.vercel.app">
	<meta name="twitter:card" content="summary_large_image">
	<meta name="twitter:title" content="GridCraft: A Powerful SvelteKit Data Grid Solution">
	<meta name="twitter:description" content="Empower your projects with GridCraft, the comprehensive data grid library designed for developers. Streamline data management, enhance user experience, and unleash the full potential of your applications. Get started now!">
	<meta name="twitter:image" content="https://grid_craft.vercel.app/webpage.jpg">
</svelte:head>

<Header />

<Hero />

<HeroGrid />

<Footer />