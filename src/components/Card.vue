<template>
  <div
    class="text-white p-6 rounded-xl border border-cyan-300 shadow-[0_0_20px_1px_rgba(34,211,238,0.3)] transition-all duration-300 w-full max-w-xs h-[45vh] flex flex-col justify-between"
  >
    <h2 class="text-xl font-semibold text-cyan-300 mb-2">{{ title }}</h2>
    <p class="text-gray-300 mb-4">
      Diese Karte hat einen feinen türkisfarbenen Glow – modern, clean und
      subtil.
    </p>
    <button
      class="px-4 py-2 rounded-md bg-cyan-500 hover:bg-cyan-400 text-white transition-colors"
    >
      Weiter
    </button>
  </div>
</template>

<script>
export default {
  props: ["title"],
};
</script>
