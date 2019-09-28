<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe658;</div>
    </div>
    <div class="header-input">
      <span class="iconfont">&#xe63c;</span>
      输入游玩主题
    </div>
    <div class="header-right">
      城市
      <span class="iconfont">&#xe659;</span>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style scoped>
.header {
  display: flex;
  line-height: 43px;
  background: #00bcd4;
  color: #fff;
}
.header-left {
  width: 32px;
  float: left;
}
.header-input {
  flex: 1;
  height: 32px;
  line-height: 32px;
  margin-top: 5px;
  margin-left: 5px;
  padding-left: 5px;
  background: #fff;
  border-radius: 10px;
  color: #ccc;
}
.header-right {
  width: 50px;
  float: right;
  text-align: center;
}
.back-icon {
  text-align: center;
  font-size: 20px;
}
</style>
