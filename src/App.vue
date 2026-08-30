<script setup>
import Hero from './components/Hero.vue'
import Menu from './components/Menu.vue'
</script>

<template>
  <Hero />
  <section class="bg-stone-100 px-6 py-24 text-stone-950 md:px-8">
  <div class="mx-auto flex max-w-6xl flex-col items-center gap-12 md:flex-row">

    <div class="w-full md:w-1/2">
      <p class="text-sm tracking-widest text-stone-500">
        CONCEPT
      </p>

      <h2 class="mt-4 text-3xl font-medium md:text-5xl">
        自分らしさを、大切に。
      </h2>

      <p class="mt-6 max-w-lg leading-relaxed text-stone-600">
        髪を整えるだけではなく、
        自分自身を好きになれる時間を提供します。
      </p>
    </div>

    <div class="w-full md:w-1/2">
      <img
        class="h-[400px] w-full rounded-2xl object-cover"
        src="/images/Concept.png"
        alt="サロンのコンセプト"
      />
    </div>

  </div>
</section>
  <Menu />
</template>
