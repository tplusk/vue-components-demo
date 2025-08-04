<template>
  <div class="">
    <h1>Contact Us</h1>
    <button-counter></button-counter>
    <p>Please send an e-mail to {{ email }}</p>
  </div>
</template>

<script setup>
import { ref } from "vue";

const email = ref("hello@dotnetmastery.com");
</script>
