<template>
  <div id="app">
        <Payment></Payment>
  </div>
</template>

<script>
import Payment from './views/payment.vue'

export default {
  name: 'app',
  components: {
    Payment
  }
}
</script>
<style lang="scss">
@import './scss/settings.scss';
@import '@/scss/base.scss';
</style>
