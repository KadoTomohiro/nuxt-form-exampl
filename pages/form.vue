<template>
  <div>
    <form>
      <div>
        <label for="name">氏名</label
        ><input id="name" type="text" /><span></span>
      </div>
      <div>
        <label for="zipcode">郵便番号</label
        ><input id="zipcode" type="text" /><span></span>
      </div>
      <div>
        <label for="address">住所</label
        ><input id="address" type="text" /><span></span>
      </div>
      <div>
        <label for="contact"></label
        ><input id="contact" type="text" /><span></span>
      </div>
      <div>
        <label for="accept"></label
        ><input id="accept" type="text" /><span></span>
      </div>
    </form>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style scoped>
div {
  color: red;
}
</style>
