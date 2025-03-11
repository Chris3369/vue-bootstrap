<template>
  <div class="container">

    <div class="p-5 mb-4 bg-light rounded-3">
      <InputText type="text" v-model="value" />
      <Button>Orange</Button>

    </div>
  </div>
</template>

<script setup lang='ts'>

import InputText from 'primevue/inputtext'

import Button from 'primevue/button'

import { ref } from 'vue'

const value = ref('');

</script>

<style></style>