<template>    
    <div id="login">
        
        <transition name="slide-left">  
   <router-view></router-view>
  </transition>
        <!-- <router-view></router-view> -->
    </div>
</template>
<script>
export default {
    data(){
        return{
        }
    }
}
</script>
<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>