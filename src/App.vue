<template>
  <!-- <router-view /> -->
  <IndexPage></IndexPage>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import IndexPage from './pages/IndexPage.vue';

export default defineComponent({
  name: 'App',
  components:{
    IndexPage,
  }
})
</script>
