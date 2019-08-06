<template>
  <div class="hey">
    <h1 id="heybabe">Hey babe,</h1>
    <h1 id="question">can I cook Risotto<br>for you tonight?</h1>
  </div>
</template>

<script>
export default {
  name: 'HeyBabe',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#heybabe {
  margin: 0;
  padding-top: 25%;
  color: red;
}
#question {
  margin: 0;
  padding-top: 100%;
  color: red;
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
