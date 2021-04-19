<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
Enter the live sensors data to know which part of the pump is malfunctioning.
    </p>
    <body>

<h1>The input element</h1>

<form action="/action_page.php">
  <label for="fname">SENSOR 1:</label>
  <input type="text" id="S1" name="S1"><br><br>
  <label for="lname">SENSOR 2:</label>
  <input type="text" id="s2" name="s2"><br><br>
  <label for="fname">SENSOR 3 :</label>
  <input type="text" id="s3" name="s3"><br><br>
  <label for="lname">SENSOR 4:</label>
  <input type="text" id="s4" name="s4"><br><br>
  
    <label for="fname">SENSOR 5:</label>
  <input type="text" id="s5" name="s5"><br><br>
  <label for="lname">SENSOR 6:</label>
  <input type="text" id="s6" name="s6"><br><br>
    <label for="fname">SENSOR 7:</label>
  <input type="text" id="s7" name="s7"><br><br>
  <label for="lname">SENSOR 8:</label>
  <input type="text" id="s8" name="s8"><br><br>
    <label for="fname">SENSOR 9:</label>
  <input type="text" id="s9" name="s9"><br><br>
  <label for="lname">SENSOR 10:</label>
  <input type="text" id="s10" name="s10"><br><br>
    <label for="fname">SENSOR 11:</label>
  <input type="text" id="s11" name="s11"><br><br>
  <label for="lname">SENSOR 12:</label>
  <input type="text" id="s12" name="s12"><br><br>
    <label for="fname">SENSOR 13:</label>
  <input type="text" id="s13" name="s13"><br><br>
  <label for="lname">SENSOR 14:</label>
  <input type="text" id="s14" name="s14"><br><br>
    <label for="fname">SENSOR 16:</label>
  <input type="text" id="s16" name="s16"><br><br>
  <label for="lname">SENSOR 17:</label>
  <input type="text" id="s17" name="s17"><br><br>
    <label for="fname">SENSOR 18:</label>
  <input type="text" id="s18" name="s18"><br><br>
  <label for="lname">SENSOR 19:</label>
  <input type="text" id="s19" name="s19"><br><br>
    <label for="fname">SENSOR 20:</label>
  <input type="text" id="s20" name="s20"><br><br>
  <label for="lname">SENSOR 21:</label>
  <input type="text" id="s21" name="s21"><br><br>
    <label for="fname">SENSOR 22:</label>
  <input type="text" id="s22" name="s22"><br><br>
  <label for="lname">SENSOR 23:</label>
  <input type="text" id="s23" name="s23"><br><br>
    <label for="fname">SENSOR 24:</label>
  <input type="text" id="s24" name="s24"><br><br>
  <label for="lname">SENSOR 25:</label>
  <input type="text" id="s25" name="s25"><br><br>
    <label for="fname">SENSOR 26:</label>
  <input type="text" id="s26" name="s26"><br><br>
  <label for="lname">SENSOR 27:</label>
  <input type="text" id="s27" name="s27"><br><br>
    <label for="fname">SENSOR 28:</label>
  <input type="text" id="s28" name="s28"><br><br>
  <label for="lname">SENSOR 29:</label>
  <input type="text" id="s29" name="s29"><br><br>
    <label for="fname">SENSOR 30:</label>
  <input type="text" id="s3" name="s30"><br><br>
  <label for="lname">SENSOR 31:</label>
  <input type="text" id="s31" name="s31"><br><br>
    <label for="fname">SENSOR 32:</label>
  <input type="text" id="s32" name="s32"><br><br>
  <label for="lname">SENSOR 33:</label>
  <input type="text" id="s33" name="s33"><br><br>
    <label for="fname">SENSOR 34:</label>
  <input type="text" id="s34" name="s34"><br><br>
  <label for="lname">SENSOR 35:</label>
  <input type="text" id="s35" name="s35"><br><br>
    <label for="fname">SENSOR 36:</label>
  <input type="text" id="s36" name="s36"><br><br>
  <label for="lname">SENSOR 37:</label>
  <input type="text" id="s37" name="s37"><br><br>
    <label for="fname">SENSOR 38:</label>
  <input type="text" id="s38" name="s38"><br><br>
  <label for="lname">SENSOR 39:</label>
  <input type="text" id="s39" name="s39"><br><br>
    <label for="fname">SENSOR 40:</label>
  <input type="text" id="s40" name="s40"><br><br>
  <label for="lname">SENSOR 41:</label>
  <input type="text" id="s41" name="s41"><br><br>
    <label for="fname">SENSOR 42:</label>
  <input type="text" id="s42" name="s42"><br><br>
  <label for="lname">SENSOR 43:</label>
  <input type="text" id="s43" name="s43"><br><br>
    <label for="fname">SENSOR 44:</label>
  <input type="text" id="s44" name="s44"><br><br>
  <label for="lname">SENSOR 45:</label>
  <input type="text" id="s45" name="s45"><br><br>
    <label for="fname">SENSOR 46:</label>
  <input type="text" id="s46" name="s46"><br><br>
  <label for="lname">SENSOR 47:</label>
  <input type="text" id="s47" name="s47"><br><br>
    <label for="fname">SENSOR 48:</label>
  <input type="text" id="s48" name="s48"><br><br>
  <label for="lname">SENSOR 49:</label>
  <input type="text" id="s49" name="s49"><br><br>
    <label for="fname">SENSOR 50:</label>
  <input type="text" id="s50" name="s50"><br><br>
  <button v-on:click="say('ALL THE VALUES SENT TO DATABASE SUCCESSFULLY')">Submit</button>
  
  
</form>



</body>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
methods: {
    say: function (message) {
      alert(message)
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
