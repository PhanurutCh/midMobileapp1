<template>
  <div class="testmid1">
    <h1>{{test}}<br></h1>
    <input type="text" name="" value="" v-model="test"><br>
    <h1>{{test2}}</h1>
    <input type="text" name="" value="" v-bind="test2">

  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      test: '',
      test2: 'test55555'
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
