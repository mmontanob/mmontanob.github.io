<template>
  <div class="hello">
    <h1>
      {{ msg }}
    </h1>
    <div class="division-block">
      <div class="divisor"></div>
      <a target="_blank" href="https://github.com/mmontanob"><i class="fa fa-github-alt" aria-hidden="true"></i></a>
      <a target="_blank" href="https://www.linkedin.com/in/mmontanob/"><i class="fa fa-linkedin-square" aria-hidden="true"></i></a>
      <a target="_blank" href="https://www.instagram.com/mmontanobe/"><i class="fa fa-instagram" aria-hidden="true"></i></a>
      <div class="divisor"></div>
    </div>
    <p><b>Software Developer</b> from Costa Rica. Passionate about <b>Artificial Inteligence</b>, <b>Web Development</b>, <b>Video Games</b>, <b>Art</b> and <b>Music</b>. Graduated from <b>ITCR</b> in 2016 as a <b>Computer Engineer</b>. Always learning something new.</p>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  text-align: center;
  color: #ff533d;
  font-size: 5em;
  margin-bottom: 0.25em;
  margin-top: 2.5em;
  position: relative;
}

.division-block > * {
  display: inline-block;
  color: #ab987a;
}

.divisor {
  width: 7%;
  margin: 0 auto;
  border-top: 1px solid #ab987a;
  height: 30%;
}

p {
  color: #f5f5f5;
  text-align: center;
  width: 50%;
  margin: 1em auto;
}

p b {
  color: #ab987a;
  font-weight: 500;
}
</style>
