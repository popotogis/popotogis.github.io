<template>
  <img class="popotogisLogo" src="./assets/img/popotogis.jpg" width="200" height="200"/>
  <Profile/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Profile from './components/Profile.vue';

export default defineComponent({
  name: 'App',
  components: {
    Profile
  }
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  img{
    width: 30px;
    height: 30px;
  }
  color: #2c3e50;
  margin-top: 30px;
  margin-left: 30px;
}
</style>
