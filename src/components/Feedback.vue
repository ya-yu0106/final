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
<form action="form_action.asp" method="get">
  First name <input type="text" name="fname"/>
  Last name <input type="text" name="lname" />
  Feedback <textarea id="feedback" name="feedback" rows="5" cols="17"></textarea>
  <button type="submit" value="Submit">Submit</button>
  <button type="reset" value="Reset">Reset</button>
</form>    
</div>
</template>


<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Feedback'
    }
  }
}
</script>



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
;
}
form {
    margin: auto;
    position: absolute ;
    top:350px; bottom:0; left:0; right:0;
padding: 0;
min-width: 140px;
max-width: 140px;
width: 500px;

}

form textarea{
  height:100px;
  resize: none;
  margin: auto;
    position: relative ;
}

</style>
