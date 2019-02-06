<template>
  <header id="header">
    <h1>Portfolio</h1>
    <ul class="socialBtn">
			<li class="twitter"><a href="https://twitter.com/jagio0129"><img src="../assets/header/icon_twitter.png" alt="Twitter"></a></li>
			<li class="last"><a href="https://www.facebook.com/yuichi.tokuda.5"><img src="../assets/header/icon_blog.png" alt="Blog"></a></li>
		</ul>
    <nav id="header-nav">
      <ul>
        <router-link tag="li" id="home-nav" to="/" exact><a>Home</a></router-link>
        <router-link tag="li" id="about-nav" to="/about"><a>About</a></router-link>
        <router-link tag="li" id="blog-nav" to="/blog"><a>Blog</a></router-link>
      </ul>
    </nav>
  </header>
</template>
<!-- style中身は省略 -->
<style scoped>
header {
    position: relative;
    max-width: 960px;
    height: 270px;
    margin: 0 auto;
    background-color: #cccccc;
}

header h1 {
    position: absolute;
    top: 50px;
    left: 0;
}

.socialBtn {
    position: absolute;
    top: 50px;
    right: 10px;
}
.socialBtn li {
    display: inline;
    margin-right: 14px;
}

#header-nav {
    position: absolute;
    bottom: 30px;
    right: 0;
}

#header-nav ul {
  list-style: none;
  margin: 0;
  padding: .2em 2em;
  float: right;
}

#header-nav ul li {
  display: inline-block;
  margin: 0;
  padding: .2em .7em;
}

#header-nav ul li a {
    display: inline;
    font-size: 14px;
    font-weight: 400;
    letter-spacing: 0.1em;
}
</style>