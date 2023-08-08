<template>  
  <div>  
      <button @click="getOne">点击获取h1</button>  
  </div>  
</template>  
<script>  
export default {  
  data() {  
      return {  
          name:'叮当猫'  
      };  
  },  
  methods: {  
      getOne(){  
          this.getNameFun( "***"+this.name+"***")  
      },
  },  
  props:{  
      getNameFun:{  
          type:Function,  
      },  
  }  
};  
</script>  