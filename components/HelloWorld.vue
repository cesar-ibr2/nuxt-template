<script lang="ts" setup>
import { ref } from 'vue'

const props = defineProps<{
  message: string
}>()

const msg = ref(props.message ?? 'World')
</script>
<template>
  <div>
    <h1>Hello {{ msg }}</h1>
  </div>
</template>
