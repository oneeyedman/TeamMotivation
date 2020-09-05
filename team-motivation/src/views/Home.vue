<template>
  <div class="home d-flex flex-column justify-center align-center pt-6 pb-6" height="100%">
    <MotivationDash  class="flex-grow-1" />
    <MotivationForm />
  </div>
</template>

<style scoped>
  .align-space-around {
    align-items: space-around;
  }
</style>

<script>
// @ is an alias to /src
import MotivationDash from '@/components/MotivationDash.vue';
import MotivationForm from '@/components/MotivationForm.vue';

export default {
  name: 'Home',
  components: {
    MotivationDash,
    MotivationForm,
  },
};
</script>
