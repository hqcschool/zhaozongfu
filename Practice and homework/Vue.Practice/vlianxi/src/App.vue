<template>  
  <div id="app">  
    <refDemo :getNameFun="getName"  />  
  </div>  
</template>  
  
<script>  
import refDemo from './components/StudentClass.vue';   
  
export default {  
  components: {  
    refDemo  
  },  
  methods:{  
    getName(name){  
      console.log(name);  
    }  
  }  
}  
</script>  
