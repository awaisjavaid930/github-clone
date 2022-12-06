<template>
  <div class="hello">
    <div class="container mx-auto">
      <h1>{{ msg }}</h1>
      Tailwind CSS Configure

        <button class="p-3  rounded-full border-solid border-3 text-white border-sky-700 bg-sky-500/100">Save Changes</button>

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
h3 {
  margin: 40px 0 0;
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
