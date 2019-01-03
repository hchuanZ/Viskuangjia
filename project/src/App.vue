<template>
  <div id="app">
    <p>已选图表：</p>

   
    <ul>
      <li v-on:click='buju(1)'>布局1</li>
      <li v-on:click='buju(2)'>布局2</li>
      <li v-on:click='buju(3)'>布局3</li>
      <li v-on:click='buju(4)'>布局4</li>
    </ul>
     <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods:{
    buju:function(num){

    }
  }
}
</script>

<style scoped>
#app {
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;*/


}
p{
  color: #FFF;
}
li{
  color: #FFF;
}
</style>
