<template>
  <div id="app">
    <span class="icon-eye"></span>
    
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import HelloWorld from './components/HelloWorld.vue';

export default Vue.extend({
  name: 'app',
  components: {
    HelloWorld,
  },
  data(){
    return{
      test: '' as string
    }
  },
  methods:{
    showTest(): string{
      return "ss";
    }
  }
});
</script>

<style lang="scss">
  @import "assets/main";
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
