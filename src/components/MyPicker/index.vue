<template>
  <picker-view v-if="visible" :indicator-style="indicatorStyle" :value="value" @change="bindChange">
    <picker-view-column>
      <view class="item" v-for="(item,index) in years" :key="index">{{item}}年</view>
    </picker-view-column>
  </picker-view>
</template>

<script>
export default {

}
</script>

<style>

</style>