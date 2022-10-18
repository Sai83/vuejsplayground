<template>
  <HeaderBar/>
  <RiskManagementVue/>
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import HeaderBar from './components/header-bar.vue';
import RiskManagementVue from './components/risk-assessment.vue';

export default {
  name: 'App',
  components: {
    HeaderBar,
    RiskManagementVue,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
