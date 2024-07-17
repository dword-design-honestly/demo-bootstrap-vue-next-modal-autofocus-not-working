<template>
  <b-button @click="isShown = true" />
  <b-modal id="isShown" v-model="isShown" :auto-focus="false">
    <b-form-input autofocus />
  </b-modal>
</template>

<script setup>
import { ref } from 'vue';

const isShown = ref(false);
</script>
