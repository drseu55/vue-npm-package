<script>
import { defineComponent } from 'vue';
import FujiTestnetLogo from '@/fuji-testnet-logo.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    FujiTestnetLogo
  }
});
</script>

<template>
  <div id="app">
    <fuji-testnet-logo />
  </div>
</template>
