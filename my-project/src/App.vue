<template>
  <div id="app">
    <div class="container">
      <h1> {{ title }} </h1>
        <Navbar />
        <Blogs />      
    </div>

  </div>
</template>

<script>
import Navbar from './Navbar'
import Blogs from './Blogs'

export default {
  name: 'app',
          components: {
            Navbar,
            Blogs
        },
  data () {
    return {
      title: "VUEJS Blog",  
    }
  }
}
</script>

<style>

body{
  background-color:#5e646d;
  font-family:sans-serif;
}
h1{
  color:#444;
  font-weight:normal;
  text-align:center;
  text-transform:uppercase;
  color:white;
}

.container{
  margin:0 auto;
  width:60%;
  text-align:center;
  color:white;
}

</style>
