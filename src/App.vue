<template>
  <div id='app'>
    <MaterialCardBox />
    <template v-slot:header>
      <strong>Card Title</strong>
    </template>
  </div>
</template>

<script>
import MaterialCardBox from './components/MaterialCardBox.vue';

export default {
  name: 'app',
  components: {
    MaterialCardBox
  }
}
</script>
