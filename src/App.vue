
/* eslint-disable */
<template>
  <div id="app">
    <div class="container knowledge-base-layout">
      <div class="row knowledge-base-wrapper">
        <div style="background:green" class="col-3 no-float">
          test
        </div>
        <div style="background:red" class="col-9 no-float">
          <div class="row" style="background:pink">search ???</div>
          <div class="row">
            <div style="background:gray" class="card col px-2">
              1 of 3
            </div>
            <div  style="background:gray" class="card col-6 px-2">
              2 of 3 (wider)
            </div>
            <div  style="background:gray" class="card col px-2">
              3 of 3
            </div>
          </div>
 
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="sass">
  @import "../node_modules/bootstrap/scss/bootstrap";
  @import "styles.scss";
</style>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 width: 100%; height: 100vh;
  /*margin-top: 60px;*/
}

.knowledge-base-wrapper{
  height:100vh;
}
.knowledge-base-layout{
  max-width:100%;
}
.card{
  margin:5px;
}

</style>
