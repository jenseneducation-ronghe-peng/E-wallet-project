<template>
  <div class="top">
    <h1>{{ title }}</h1>
    <h4>{{ subtitle }}</h4>
  </div>
</template>

<script>
export default {
  name: "Top",

  props: {
    title: String,
    subtitle: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.top {
  margin-bottom: 2rem;
}
h3 {
  margin: 40px 0 0;
}
h4 {
  color: gray;
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
