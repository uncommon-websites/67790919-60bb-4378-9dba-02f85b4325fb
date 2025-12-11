<script lang="ts">
    const bgImage = "/generated/image-electric-aircraft-in-flight-modern-evtol-1765487769302-0.webp";
</script>

<section class="relative h-screen w-full overflow-hidden bg-black text-white">
    <!-- Background Image -->
    <div class="absolute inset-0">
        <img src={bgImage} alt="Electric Aircraft in Flight" class="w-full h-full object-cover opacity-80" />
        <!-- Gradient Overlay -->
        <div class="absolute inset-0 bg-gradient-to-t from-black/70 via-transparent to-black/40"></div>
    </div>

    <!-- Content -->
    <div class="relative z-10 h-full flex flex-col justify-end px-6 pb-20 md:px-12 md:pb-32 max-w-[1400px] mx-auto">
        <h1 class="text-5xl md:text-7xl lg:text-8xl font-semibold leading-[0.95] tracking-tight max-w-4xl mb-12">
            Powering the<br />
            future of<br />
            electric aviation
        </h1>

        <!-- CTA -->
        <div class="flex items-center gap-4">
            <a href="#technology" class="bg-white text-black px-6 py-3 text-xs font-semibold uppercase tracking-wide hover:bg-gray-200 transition-colors">
                Explore Our Technology
            </a>
            <a href="#" class="flex items-center gap-2 text-sm font-medium hover:opacity-70 transition-opacity group">
                <span class="text-xs group-hover:translate-x-1 transition-transform duration-300">›</span>
                Learn about certification
            </a>
        </div>
    </div>
</section>
