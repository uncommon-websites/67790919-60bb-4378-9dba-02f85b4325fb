<script lang="ts">
    import Navbar from "$lib/components/Navbar.svelte";
    import Hero from "$lib/components/Hero.svelte";
    import Statement from "$lib/components/Statement.svelte";
    import HavenDemo from "$lib/components/HavenDemo.svelte";
    import HavenOne from "$lib/components/HavenOne.svelte";
    import ProgressCarousel from "$lib/components/ProgressCarousel.svelte";
    import Team from "$lib/components/Team.svelte";
    import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
    <title>Electric Power Systems - Certified Electric Aviation Battery Systems</title>
    <meta name="description" content="EPS delivers certified electric aviation via modular, lightweight battery systems enabling safer, longer-range flight. 50+ years aerospace certification expertise from Boeing, Rolls-Royce, and Honeywell." />
</svelte:head>

<main class="w-full min-h-screen bg-white">
    <Navbar />
    <Hero />
    <Statement />
    <HavenDemo />
    <HavenOne />
    <ProgressCarousel />
    <Team />
    <Footer />
</main>

