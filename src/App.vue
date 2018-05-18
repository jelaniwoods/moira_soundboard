<template>
  <div id="app">
    <img src="./assets/moira.png" alt="Moira">
    <!-- <Hexagon/>
    <Hexagon/>
    <Hexagon/>
    <div style="float: left; width: 400px;">
    <div class="hex2-row">
        <div class="hex2"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
        <div class="hex2 even"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
        <div class="hex2"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
    </div>
    <div class="hex2-row">
        <div class="hex2"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
        <div class="hex2 even"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
        <div class="hex2"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
    </div>
    <div class="hex2-row">
        <div class="hex2"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
        <div class="hex2 even"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
        <div class="hex2"><div class="left"></div><div class="middle"></div><div class="right"></div></div>
    </div>
</div> -->
  </div>
</template>

<script>
import Hexagon from './components/Hexagon.vue'

export default {
  name: 'app',
  components: {
    Hexagon
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: rgb(156, 142, 170);
}
 .hex-row {
        clear: left;
    }
    .hex-row.even {
        margin-left: 53px;
    }
    .hex2 {
        float: left;
        margin-right: -26px;
        margin-bottom: -50px;
    }
    .hex2 .left {
        float: left;
        width: 0;
        border-right: 30px solid #6C6;
        border-top: 52px solid transparent;
        border-bottom: 52px solid transparent;
    }
    .hex2 .middle {
        float: left;
        width: 60px;
        height: 104px;
        background: #6C6;
    }
    .hex2 .right {
        float: left;
        width: 0;
        border-left: 30px solid #6C6;
        border-top: 52px solid transparent;
        border-bottom: 52px solid transparent;
    }
    .hex2-row {
        clear: left;
    }
    .hex2.even {
        margin-top: 53px;
    }
</style>
