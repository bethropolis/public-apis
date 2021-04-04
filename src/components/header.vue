<template>
  <div>
    <h1 class="head">{{ msg }}</h1>
    <a href="http://github.com/bethropolis/public-apis" class="github"><h4>Github</h4></a>
    <hr /> 
  </div>
</template> 

<script>
export default {
  name: "appheader",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.head {
  font-size: 35px;
  font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  text-shadow: 2px 2px 3px #38CE1D;
}
.github{
  position:absolute;
  top: 10px;
  right: 20px; 
}
</style>
