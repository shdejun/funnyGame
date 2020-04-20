<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p> prodigalblack(5区怀旧服狂野之刃)</p>
    <video src="@/assets/video/3a450596d91de66eac452b7082122609.mp4" controls="controls" width="100%" height="300px">
      您的浏览器不支持 video 标签。
    </video>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to my funny video!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
