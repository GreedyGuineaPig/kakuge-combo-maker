<script setup>

</script>

<template>
  <div id="app">
  <w-app>
    <header>GGST combo maker</header>
      <w-flex wrap class="text-center">
        <div class="xs6 pa1">
          <div class="xs6 pa1">
            <w-button class="ma1" bg-color="pink-light2" shadow>5P</w-button>
            <w-button class="ma1" bg-color="pink-light2" shadow>2P</w-button>
            <w-button class="ma1" bg-color="pink-light2" shadow>6P</w-button>
          </div>
          
          <div class="xs6 pa1">
            <w-button class="ma1" bg-color="blue" shadow>5K</w-button>
            <w-button class="ma1" bg-color="blue" shadow>2K</w-button>
            <w-button class="ma1" bg-color="blue" shadow>6K</w-button>
          </div>
          
          <div class="xs6 pa1">
            <w-button class="ma1" bg-color="green" shadow>c.S</w-button>
            <w-button class="ma1" bg-color="green" shadow>2S</w-button>
            <w-button class="ma1" bg-color="green" shadow>f.S</w-button>
          </div>
          
          <div class="xs6 pa1">
            <w-button class="ma1" bg-color="red" shadow>5HS</w-button>
            <w-button class="ma1" bg-color="red" shadow>2HS</w-button>
            <w-button class="ma1" bg-color="red" shadow>6HS</w-button>
          </div>

          <div class="xs6 pa1">
            <w-button class="ma1" bg-color="orange" shadow>5D</w-button>
            <w-button class="ma1" bg-color="orange" shadow>5D (charged)</w-button>
            <w-button class="ma1" bg-color="orange" shadow>2D</w-button>
          </div>

          <div class="xs6 pa1">
            <w-button class="ma1" bg-color="pink-light2" shadow>j.P</w-button>
            <w-button class="ma1" bg-color="blue" shadow>j.K</w-button>
            <w-button class="ma1" bg-color="green" shadow>j.S</w-button>
            <w-button class="ma1" bg-color="red" shadow>j.HS</w-button>
            <w-button class="ma1" bg-color="orange" shadow>j.D</w-button>
          </div>
        </div>
        <div class="xs6 pa1">
          <div class="primary--bg py3">xs6</div>
        </div>
      </w-flex>
    <footer>Footer</footer>
  </w-app>
  </div>
</template>

<style scoped>
.w-app {padding: 4px;background-color: #fffeed;}
header, footer, aside, main {
  margin: 4px;
  padding: 12px;
  text-transform: uppercase;
  color: #666;
  border: 1px solid rgba(0, 0, 0, 0.07);
}
header, footer {background-color: #e9f8fe;min-height: 60px;}
aside {background-color: #fef2ff;}
main {background-color: #efffed;}
</style>
