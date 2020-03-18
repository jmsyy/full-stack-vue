<template>
  <div>
    <h1>Jerry</h1>
    <div>{{age}}</div>
  </div>
</template>

<script>
import Student from './Student.vue';

export default {
  mixins: [Student],
  data() {
    return {
      name: 'Jerry',
      age: 20
    },
  }
}
</script>

<style lang="scss" scoped>

</style>