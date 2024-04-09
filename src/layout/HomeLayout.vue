<template>
  <div class="min-h-screen flex flex-col justify-between">
    <div><Header /> <Bodys /></div>

    <Footers />
  </div>
</template>

<script setup>
import Bodys from "../components/Bodys.vue";
import Footers from "../components/Footers.vue";
import Header from "../components/Header.vue";
</script>

<style lang="scss" scoped></style>
