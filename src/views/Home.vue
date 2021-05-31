<template>
  <div class="home">
    <player />
    <bubbles />
  </div>
</template>

<script>
import Player from '../components/Player.vue'
import Bubbles from '../components/Bubbles.vue'

export default {
  components: {
    Player,
    Bubbles
  }
}
</script>

<style lang="scss">
.home {
  position: relative;
  z-index: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  background-color: #FADDE1;
}
</style>
