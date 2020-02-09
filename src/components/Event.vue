<template>
  <div>
    <p @click="msg">test</p>
  </div>
</template>

<script>
  export default {
    name: "Event",
    data(){
      return {
        count: 0
      }
    },
    methods: {
      msg() {
        this.count += 1;
      }
    }
  }
</script>

<style scoped>

</style>
