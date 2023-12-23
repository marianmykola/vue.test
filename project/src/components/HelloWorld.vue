<!-- HelloWorld.vue -->

<template>
  <div>
    <h1>{{ message }}</h1>
    <input v-model="userInput" placeholder="Type a message...">
    <p>You typed: {{ userInput }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: 'Hello, Vue!',
      userInput: ''
    };
  }
};
</script>

<style scoped>
/* Add optional scoped styles here */
</style>
