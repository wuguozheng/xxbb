<template>
 <div>
   <div class="rap">
     <div class="rap-1">
       <img data-v-7629dae3="" src="https://static.shiyanlou.com/frontend/dist/img/9f43b00.svg" alt="实验楼" width="130" height="70">
       <div>做实验，学编程</div>
       <div class="rap-2">
         <div class="timi-1">企业版 | 学校版</div>
         <div class="timi-2">登录</div>
         <div class="timi">注册</div>
       </div>
     </div>
   </div>
 </div>
</template>

<script>

 export default {
   name: '',
   props: {
   },
   components: {
     
   },
   data () {
     return {

     }
   },
   methods: {

   },
   mounted() {

   },
   watch: {

   },
   computed: {

   }
 }
</script>

<style scoped lang='scss'>
.rap {
  width: 100%;
  height: 200px;
  background: skyblue;
}
.rap-1 {
  width: 1150px;
  height: 100px;
  background: slateblue;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}
.rap-2 {
  display: flex;
  width: 300px;
  height: 100px;
  background: springgreen;
  justify-content: space-between;
  align-items: center;
  position: absolute;
  right: 0;
}
.timi {
  width: 80px;
  height: 50px;
  background: skyblue;
  display: flex;
  justify-content: center;
  align-items: center;
  color: whitesmoke;
}
.timi-1 {
  color: #ccc;
}
.timi-2 {
  color: skyblue;
}
</style>