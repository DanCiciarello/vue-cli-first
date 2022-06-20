<template>
  <div>
    <div class="container text-center py-5">
      <div class="row">
        <PageTitle></PageTitle>
      </div>
      <div class="row py-5">
        <JumboTron></JumboTron>
      </div>
    </div>
  </div>
</template>

<script>

import PageTitle from './components/PageTitle.vue';
import JumboTron from './components/JumboTron.vue';

export default {
  components: {
    PageTitle,
    JumboTron,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
