<template>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.6.2/css/bootstrap.min.css"
    integrity="sha512-rt/SrQ4UNIaGfDyEXZtNcyWvQeOq0QLygHluFQcSjaGB04IxWhal71tKuzP6K8eYXYB6vJV4pHkXcmFGGQ1/0w=="
    crossorigin="anonymous"
    referrerpolicy="no-referrer"
  />
  <div id="app">
    <div class="signInContainer">
      <img
        alt="Vue logo"
        src="https://www.endless-web-worlds.com/assets/img/Endless%20Web%20Worlds.png"
        style="width: 100%; max-width: 556px"
      />
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background: purple;
  height: 100svh;
}

.signInContainer {
}
</style>
