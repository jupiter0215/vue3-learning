<template>
  <div id="app">
    <Counter msg="Welcome to counter component" />
  </div>
</template>

<script>
import Counter from './components/Counter.vue';

export default {
  name: 'App',
  components: {
    Counter,
  },
};
</script>
