<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
</template>



<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #009DFF;
}

.card {
    margin: .70rem .5rem 1rem 3.5rem; /* Added */
    float: left; /* Added */
    margin-bottom: 10px; /* Added */
    border-color: #009DFF;

}

strong{
  color: #009DFF;
}

p{
  opacity: 80%;
}

.card-title{
  opacity: 60%;
}

.btn-primary{
  background-color: #009DFF;
  border-color: white;
}

</style>
