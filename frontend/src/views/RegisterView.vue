<template>
    <RegisterForm />
  </template>
  
  <script lang="ts">
  import { defineComponent } from 'vue';
  import RegisterForm from '../components/forms/RegisterForm.vue';
  
  export default defineComponent({
    name: 'RegisterView',
    components: {
      RegisterForm,
    },
  });
  </script>