<template>
  <div>
    <div class="rap">
      <div class="rap-1">
        <div class="left">
          <img
            data-v-7629dae3
            src="https://static.shiyanlou.com/frontend/dist/img/9f43b00.svg"
            alt="实验楼"
            width="130"
            height="70"
          />
          <div>做实验，学编程</div>
        </div>
        <div class="rap-2">
          <div class="timi-1">企业版 | 学校版</div>
          <div class="timi-2">登录</div>
          <div class="timi">注册</div>
        </div>
      </div>
      <div class="run">
        <img src="../home/QQ截图20200601133655.png" alt="" width="300" height="80">
        <div class="run-1">
          <div class="ki">路径</div>
          <div class="ki2">训练营</div>
          <div class="ki3">楼+</div>
          <div class="ki4">会员</div>
          
         <div class="ki5">社区 <i class="iconfont icon-xiajiantou"></i></div>
        </div>
         <div class="ki6"><img src="https://static.shiyanlou.com/frontend/dist/img/02a4001.svg" class="tag" data-v-ac00dc36=""></div>
        <div class="run-2">
          <input type="text" placeholder="  搜索 课程/问答" class="run-3" >
          <div class="tes-1"><i class="iconfont icon-sousuo item3"></i></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "",
  props: {},
  components: {},
  data() {
    return {};
  },
  methods: {},
  mounted() {},
  watch: {},
  computed: {}
};
</script>

<style scoped lang='scss'>
.rap {
  width: 100%;
  height: 180px;
  background: whitesmoke;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.rap-1 {
  width: 1200px;
  height: 100px;
  background: transparent;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}
.left {
  position: absolute;
  left: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
.rap-2 {
  display: flex;
  width: 300px;
  height: 100px;
  background: transparent;
  justify-content: space-between;
  align-items: center;
  position: absolute;
  right: 0;
}
.timi {
  width: 80px;
  height: 50px;
  background: rgb(8, 191, 145);
  display: flex;
  justify-content: center;
  align-items: center;
  color: whitesmoke;
  &:hover {
    cursor: pointer;
  }
}
.timi-1 {
  color: #ccc;
  &:hover {
    cursor: pointer;
    color: rgb(8, 191, 145);
  }
}
.timi-2 {
  color: rgb(8, 191, 145);
  &:hover {
    cursor: pointer;
    color: #ccc;
  }
}
.run {
  width: 1200px;
  height: 80px;
  background: white;
  display: flex;
  position: relative;
}
.run-1 {
  width: 400px;
  height: 80px;
  background: transparent;
  display: flex;
  justify-content: space-around;
  align-items: center;
  font-size: 20px;
  &:hover {
    cursor: pointer;
  }
}
.run-2 {
  position: absolute;
  right: 20px;
  margin-top: 25px;
}
.run-3 {
  width: 220px;
  height: 35px;
  border: 1px solid #ccc;
  border-radius: 6px;
  &:hover{
    outline: none;
    border: 1px solid rgb(8, 191, 145);
  }
}
.ki:hover {
  cursor: pointer;
   color: rgb(8, 191, 145);
}
.ki2:hover {
  cursor: pointer;
   color: rgb(8, 191, 145);
}
.ki3:hover {
  cursor: pointer;
   color: rgb(8, 191, 145);
}
.ki4:hover {
  cursor: pointer;
   color: rgb(8, 191, 145);
}
.ki5:hover {
  cursor: pointer;
   color: rgb(8, 191, 145);
}
.ki6 {
  margin-left: -106px;
  margin-top: 14px;
  &:hover {
    cursor: pointer;
  }
}
.tes-1 {
  position: absolute;
  right: 20px;
  top: 8px;
}
</style>