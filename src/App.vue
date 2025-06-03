<template>
  <div
    class="min-h-screen grid grid-cols-[auto_1fr_auto] grid-rows-[auto_1fr_auto] bg-stone-950"
  >
    <div class="p-4">
      <Card title="Oben Links" />
    </div>
    <div></div>
    <div class="p-4 flex justify-end">
      <Card title="Oben Rechts" />
    </div>

    <div></div>
    <div></div>
    <div></div>

    <div class="p-4">
      <Card title="Unten Links" />
    </div>
    <div></div>
    <div class="p-4 flex justify-end">
      <Card title="Unten Rechts" />
    </div>
  </div>
</template>

<script>
import Card from "./components/Card.vue";
export default {
  components: { Card },
};
</script>
