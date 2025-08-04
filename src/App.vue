<template>
  <div>{{ message }}</div>
  <!-- local component -->
  <ContactUs></ContactUs>
  <ButtonCounter></ButtonCounter>
</template>

<script setup>
import ContactUs from "./components/ContactUs.vue";
import ButtonCounter from "./components/ButtonCounter.vue";

const message = "Hello Vue";
</script>

<style></style>
