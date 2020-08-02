<template>
  <div>
    <nav>
      <img src="../assets/logo.png" href="www.mmontanob.com" />
      <ul>
        <li>Projects</li>
        <li>Blog</li>
        <li>Other</li>
      </ul>
    </nav>
  </div>
</template>

<style scoped>
nav {
  background: #0f1626;
  height: 4em;
  color: #f5f5f5;
  /* box-shadow: 0 2px 25px #ab987a; */
  text-align: center;
}

nav ul {
  margin: 0;
  list-style: none;
  display: inline-block;
  vertical-align: top;
  height: 100%;
}

nav ul li {
  display: inline-block;
  height: 100%;
  padding-top: 1.25em;
  margin: 0 1em;
}

nav img {
  height: 100%;
  padding: 0.75em;
  box-sizing: border-box;
  display: inline-block;
}
</style>