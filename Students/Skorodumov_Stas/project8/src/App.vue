<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Shop</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/home">Home</router-link>
    </div>
    <router-view/>
  </div>
</template>




<style lang="scss">
    .small {
        font-size: 1em
    }
    
    .big {
        font-size: 2em
    }

    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        position: relative;
        z-index: 1;
    }

    #nav {
        position: absolute;
        top: 67px;
        left: 605px;
        z-index: 4;
        text-transform: uppercase;
        font-weight: bold;
        font-size: 1em;        
    }



    #nav {
    /* padding: 30px; */

        a {
            font-weight: bold;
            color: #6386a8;

            &.router-link-exact-active {
            color: #42b983;
            }
        }
    }    
</style>
