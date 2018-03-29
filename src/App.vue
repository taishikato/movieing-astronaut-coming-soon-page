<template>
  <div id="app">
    <div id="main" class="has-text-centered">
      <h1 class="title is-1">Movieing Astronaut 🚀👩‍🚀👨‍🚀🎥</h1>
      <h2 class="title is-2">Coming Soon!!</h2>
      <h3 class="title is-3">
        <a href="https://www.facebook.com/MovieingAstronaut/" target="_blank"><i class="fab fa-facebook-square"></i></a>
        <a href="https://twitter.com/mvingastronaut" target="_blank"><i class="fab fa-twitter-square"></i></a>
        <a href="https://github.com/taishikato/movieing-astronaut-coming-soon-page" target="_blank"><i class="fab fa-github-square"></i></a>
      </h3>
    </div>
    <vue-particles
      color="#dedede"
      :particleOpacity="0.7"
      :particlesNumber="80"
      shapeType="circle"
      :particleSize="4"
      linesColor="#dedede"
      :linesWidth="1"
      :lineLinked="true"
      :lineOpacity="0.4"
      :linesDistance="150"
      :moveSpeed="3"
      :hoverEffect="true"
      hoverMode="grab"
      :clickEffect="true"
      clickMode="push"
    >
    </vue-particles>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
html, body, #app {
    height: 100%;
}

#app {
  position: relative;
  background-image: url('https://res.cloudinary.com/guidesquare/image/upload/v1522334423/movieing-astronaut-bg_pfupzr.jpg');
  background-size: cover;
}

#main {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translateY(-50%) translateX(-50%);
}

h1,h2 {
  color: #fff !important;
  text-shadow: 5px 5px 0px #000000;
  font-family: 'Dosis', sans-serif;
}

a {
  color: #fff !important;
}
</style>
