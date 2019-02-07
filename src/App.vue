<template>
  <div id="app">
    <h1>Jagio's Page</h1>
    <ul class="socialBtn">
      <li><a href="https://twitter.com/jagio0129"><img src="./assets/icon_twitter.png" alt="Twitter"></a></li>
      <li><a href="https://twitter.com/jagio0129"><img src="./assets/icon_blog.png" alt=""></a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
/*
body {
  background-image: url("./assets/back.jpg");
  background-repeat:no-repeat;
  background-position: center center;
}
*/
h1 {
  font-family: 'Dancing Script', cursive;
  font-size: 100px;
  /*line-height: 360px;*/
  font-weight: 400;
  src: url(https://fonts.googleapis.com/css?family=Dancing+Script) format('woff');
}

#top_img {
  text-align:center;
}

.socialBtn li {
    display: inline;
    margin-right: 14px;
}
</style>
