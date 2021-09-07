<template>
  <div class="jumbotron">
    <h1>Hello, world!</h1>
    <hr/>
    <p>
      This is a simple hero unit, a simple jumbotron-style component for calling
      extra attention to featured content or information.
    </p>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style scoped>
.jumbotron {
  margin-top: 40px;
  padding: 20px 40px;
  background: lightblue;
}

h1 {
  color: dodgerblue;
}

hr {
  margin: 35px;
}
</style>