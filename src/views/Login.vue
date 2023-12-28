<template>
  <button @click="login">Login</button>
</template>

<script setup>
const login = () => {
  // Redirect to the OAuth login URL (replace with your actual URL)
  window.location.href = "http://localhost:8000/login";
};
</script>
