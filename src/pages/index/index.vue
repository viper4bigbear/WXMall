<template>
  <div>
    <div class="header">
      <icon type="search"></icon>
      <input type="text" placeholder="搜索">
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style lang="less">
.header {
  position: relative;
  background-color: #ff2d4a;
  padding: 20rpx 16rpx;
  icon {
    position: absolute;
    z-index: 998;
    left: 50%;
    top: 30rpx;
    transform: translateX(-200%);
  }
  input {
    width: 100%;
    height: 60rpx;
    background-color: #fff;
    text-align: center;
    border-radius: 8rpx;
  }
}
</style>
