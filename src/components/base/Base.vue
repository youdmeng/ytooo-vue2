<template>
  <el-container class="main">
    <el-aside>Aside</el-aside>
    <el-main>Main</el-main>
  </el-container>
</template>

<script lang="ts">
import { Vue , Component } from 'vue-property-decorator';

@Component
export default class Base extends Vue {
  constructor() {
    super()
  }
}
</script>
<style lang="sass">
</style>