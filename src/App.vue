<template>
  <div id="container">
    <div ref="sidebar" id="sidebar" v-on:click="toggleSideBarOff">
      <div ref="toggleOff" id="toggleOff"></div>
      <div id="search"></div>
      <p> This is the sidebar </p>
    </div>
    <label ref="toggleOn" id="toggleOn" v-on:click="toggleSideBarOn">☰</label>
    <div ref="appContainer" id="app">
      <router-link to="/"> Main </router-link>
      <div></div>
      <router-view/>
      <div id="armor">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
      </div>
      <div id="info">
        <h1>This is where the info goes</h1>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'App',
    methods: {
      toggleSideBarOn: function() {
        this.$refs["sidebar"].style.left = "0%";
      },
      toggleSideBarOff: function() {
        this.$refs["sidebar"].style.left = "-25%";
      }
    }
  }
</script>

<style>
#container {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

  body {
    margin: 0px;
  }

  #container {
    display: flex;
  }

  #toggleOn {
    width: 25px;
    height: 25px;
    display: inline-block;
    background-color: aqua;
    text-align: center;
    cursor: pointer;
  }

  #toggleOff {
    width: 35px;
    height: 35px;
    background-color: aqua;
    display: inline-block;
  }

  #sidebar {
    height: 100vh;
    background-color:gray;
    width: 25%;
    position: fixed;
    transition: all 1s;
    left: -25%;
  }

  #search {
    height: 35px;
    width: 75%;
    background-color: black;
    display: inline-block;
  }

  #armor {
    height: 50px;
    width: 625px;
    padding-top: 100px;
  }

  #armor div {
    width: 50px;
    height: 50px;
    background-color: black;
    display: inline-block;
    margin-left: 25px;
  }

  #info {
    margin-left: 25px;
  }
</style>
