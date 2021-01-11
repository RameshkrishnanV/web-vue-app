<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <div style="padding-left: 50px; padding-right:50px; width:100%; overflow-x: 'scroll'; overflow-y:hidden; display: flex; text-align: center;">
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>
      <div style="width: 200px; margin: 10px">
        <h1>Item1</h1>
      </div>

    </div>
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
  margin: 40px 0 0;
  color: #FFFFFF;
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
