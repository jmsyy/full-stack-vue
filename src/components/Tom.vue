<template>
  <div>
    <h1>Tom</h1>
    <div>{{name}}</div>
  </div>
</template>

<script>
import Student from './Student.vue';

export default {
  mixins: [Student],
  data() {
    return {
      name: 'Tom',
      age: 18
    },
  }
}
</script>

<style lang="scss" scoped>

</style>