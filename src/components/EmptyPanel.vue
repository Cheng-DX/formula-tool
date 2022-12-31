<script setup lang="ts">
defineProps<{
  text: string
}>()
</script>

<template>
  <div hp-100 flex-center flex-col>
    <img class="img" src="@/assets/open-box.png">
    <span class="text" mt-2>{{ text ? text : 'No Results' }}</span>
  </div>
</template>

<style scoped>
.img {
  width: 50px;
  height: 50px;
}
.text {
  color: #c48d69;
}
</style>
