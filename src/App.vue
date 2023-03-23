<template>
  <div class="container mx-auto p-4">
    <LoginForm />
  </div>
  
</template>

<script>
import LoginForm from "./LoginForm.vue";

export default {
  name: "App",
  components: {
    LoginForm,
  },
};
</script>
