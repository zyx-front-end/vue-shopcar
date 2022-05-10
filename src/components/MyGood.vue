<template>
  <div class="my-good-item">
    <div class="left">
      <div class="custom-control custom-checkbox">
        <input type="checkbox" class="custom-control-input" id="input" />
        <label for="input">
          <img src="../assets/01.jpg" alt="" />
        </label>
      </div>
    </div>
    <div class="right">
      <div class="top">商品名字</div>
      <div class="bottom">
        <div class="price">￥100</div>
        <my-count></my-count>
      </div>
    </div>
  </div>
</template>

<script>
import MyCount from './MyCount.vue';
export default {
  components: { MyCount },};
</script>

<style lang="less" scoped>
.my-good-item {
  display: flex;
  padding: 10px;
  border-bottom: 1px solid #ccc;
  .left {
    width: 120px;
    height: 120px;
    margin-right: 8px;
    border-radius: 10px;
  }
  .right {
    flex: 1;
    display: flex;
    flex-direction: column;
    .top{
        font-size:14px;
        font-weight: 700;
    }
    .bottom{
        display: flex;
        justify-content: space-between;
        padding:5px 0;
        align-items: center;
        .price{
            color:red;
            font-weight: bold;
        }
    }
  }
}
</style>