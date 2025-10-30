<template>
  <div>
    <svg-icon icon-class="question" @click="goto" />
  </div>
</template>

<script setup lang="ts">
const url = ref('https://github.com/luckykuang/infoq-scaffold');

function goto() {
  window.open(url.value);
}
</script>
