<template>
  <div class="notes_wrapper" >
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  data(){
    return {}
  },
  created(){
    this.$store.dispatch('GET_NOTES')
  }
}
</script>

<style scoped>

</style>
