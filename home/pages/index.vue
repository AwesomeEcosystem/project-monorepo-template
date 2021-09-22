<template>
  <div class="text-white">
    <Cover/>
    <About/>
    <Network/>
    <Footer/>
  </div>
</template>

<script>

export default {
  layout: 'app',
  mounted() {
    // console.log(this.$coon);
    // if (!this.$coon.accounts[0]) {
    //   this.$router.push('start')
    // }
  }
}
</script>
