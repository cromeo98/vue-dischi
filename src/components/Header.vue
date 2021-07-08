<template>
  <header class="ps-3">

    <img id="logo" src="../assets/spotify-logo.svg" alt="">

  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

header{
  height: 60px;
  background-color: rgb(46, 58, 70);
  display: flex;
  align-items: center;
}

#logo{
  width: 45px;
}

</style>
