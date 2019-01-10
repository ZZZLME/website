<template>
  <div id="app">
    <router-view/>
    <!-- <login></login> -->
  </div>
</template>

<script>
// import login from './components/login' // 引入login.vue组件
export default {
  name: 'App',
  components: {
    // 'login': login
  }
}
</script>

<style type="text/css">
.icon {
  width: 1em;
  height: 1em;
  vertical-align: -0.15em;
  fill: currentColor;
  overflow: hidden;
}
</style>
