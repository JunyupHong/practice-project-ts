<template>
  <div id="app">
    <Header />
    <CoronaDashboard />
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import Header from '@/components/Header.vue';
import CoronaDashboard from '@/components/CoronaDashboard.vue';

export default Vue.extend({
  name: 'App',
  components: { Header, CoronaDashboard },
});
</script>

<style lang="scss" scoped></style>
