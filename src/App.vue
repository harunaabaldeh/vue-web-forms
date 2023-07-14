<script>
import SignupForm from "./components/SignupForm.vue";
export default {
  name: "app",
  components: { SignupForm },
};
</script>

<template>
  <h1>Web Forms</h1>
  <SignupForm />
</template>

<style>
#app {
  text-align: center;
  color: #444;
  margin-top: 60px;
}

body {
  margin: 0;
  background: #eee;
}
</style>
