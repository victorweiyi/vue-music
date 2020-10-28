<template>
    <div id="app">

      <!-- 头部组件 -->
      <top></top>
      <!-- 主体组件 -->
      <index></index>
  
    </div>
</template>

<script>
//导入
import top from './components/01.top.vue'
import index from './components/02.index.vue'

export default {
  name:'app',
    //注册组件
  components:{
    top,  //top:top
    index,
    
  },
  methods:{


  }
}
</script>

<style>

</style>