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
          src: "https://cdnjs.cloudflare.com/ajax/libs/phaser/3.60.0/phaser.min.js",
          body: true
        },
        {
          src: "https://cdnjs.cloudflare.com/ajax/libs/underscore.js/1.13.6/underscore-min.js",
          body: true
        },
        {
          src: "/promo_easter/appandlibs.js",
          body: true
        }
      ]
    };
  }
}
</script>
