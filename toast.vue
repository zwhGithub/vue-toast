<style>
  .wh-fade-toast-enter {
    opacity: 0
  }
  .wh-fade-toast-enter-active, .wh-fade-toast-leave-active {
    transition: opacity .4s
  }
  .wh-fade-toast-leave-active {
    opacity: 0;
  }

  * {
    margin: 0;
    padding: 0;
  }

  /* wh-toast */
  .wh-toast {
    position: fixed;
    z-index: 9999;
    line-height: 17px;
    left: 50%;
    transform: translate(-50%, 0);
    bottom: 50px;
  }

  .wh-toast-message {
    font-size: 14px;
    padding: 12px 16px;
    text-align: center;
    color: #fff;
    border-radius: 6px;
    background: #323232;
    opacity: .9;
  }
</style>
<template>
  <transition name="wh-fade-toast">
    <div v-if="is_show" class="wh-toast">
      <div class="wh-toast-message">
        {{content}}
      </div>
    </div>
  </transition>
</template>
<script>
  export default {
    data () {
      return {
        is_show: false,//是否显示toast
        duration: 1500,//停留的时间
        content: "" //显示的内容
      }
    }
  }
</script>
