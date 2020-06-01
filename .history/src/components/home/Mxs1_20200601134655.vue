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
        <div class="run-1">
          <div><img src="../home/QQ截图20200601133655.png" alt="" width="260" height="100"></div>
          <div>路径</div>
          <div>训练营</div>
          <div>楼+</div>
          <div>会员</div>
          <div>社区</div>
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
  height: 200px;
  background: whitesmoke;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.rap-1 {
  width: 1150px;
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
  width: 1150px;
  height: 100px;
  background: yellowgreen;
}
.run-1 {
  width: 650px;
  height: 100px;
  background: violet;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>