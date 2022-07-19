<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "LoginView",
  data() {
    return {
      name: "login!",
      img: "@/assets/login.jpg",
    };
  },
});
</script>

<template>
  <img :src="img" :alt="name" />
  <h1>
    {{ name }}
  </h1>
</template>

<style></style>
