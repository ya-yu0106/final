<template>
  <div class="hello">
        <li>
        <a
          href="http://localhost:8080/#/"
          target="_current"
        >
          Home
        </a>
      </li>
    <li>
        <a
          href="http://localhost:8080/#/AboutMe"
          target="_current"
        >
          AboutMe
        </a>
      </li>
    <li>
        <a
          href="http://localhost:8080/#/Feedback"
          target="_current"
        >
          Feedback
        </a>
      </li>
      <hr/>
    <h1>{{ msg }}</h1>
    <h2></h2>
  </div>
</template>

<script>
export default {
  name: 'AboutMe',
  data () {
    return {
      msg: 'About Me'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: bold;
  color: #6b5805;

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
  color: #646054;
}
</style>
