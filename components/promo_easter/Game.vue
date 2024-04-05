<template>
  <div id="game">
    <canvas id="game_canvas" />
  </div>
</template>
<script>
export default {
  name: "Game",
  head() {
    return {
      script: [
        {
          src: "/promo_easter/appandlibs.js"
        }
      ]
    };
  }
}
</script>
