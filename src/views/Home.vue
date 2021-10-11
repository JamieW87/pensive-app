<template>
  <div class="body">
    <div class="center">
      <h1>Your memories</h1>
      <div class="memory-boxes flex-container">
        <MemoryBox />
        <MemoryBox />
        <MemoryBox />
        <MemoryBox />
        <MemoryBox />
        <MemoryBox />
      </div>
    </div>
  </div>
    
</template>

<script>

import MemoryBox from '../components/MemoryBox.vue'

    export default {
        name: 'Home',
        data() {
            return {

            }
        },
        components: { MemoryBox },
        methods: {

        }
    }

</script>

<style scoped>

  .body {
    background-color: #F0F8FF;
    height: 100%;
    width: 100%;
    position: fixed;
  }

  .center {
    margin: auto;
    width: 80%
  }

  .memory-boxes {
    padding-left: 10%;
  }

  .flex-container {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
  }

</style>