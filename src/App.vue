<template>
  <div class="border-green-400 border-3 text-red-300">
    Good
    <i class="ri-home-wifi-line"></i>
    <div class="card">
    <div class="flex flex-wrap md:justify-content-between justify-content-center card-container">
        <div class="border-500 surface-overlay border-3 border-round font-bold m-2 flex align-items-center justify-content-center" style="min-width: 200px; min-height: 100px">border-500</div>
        <div class="border-cyan-500 surface-overlay border-3 border-round font-bold m-2 flex align-items-center justify-content-center" style="min-width: 200px; min-height: 100px">border-cyan-500</div>
        <div class="border-orange-500 surface-overlay border-3 border-round font-bold m-2 flex align-items-center justify-content-center" style="min-width: 200px; min-height: 100px">border-orange-500</div>
    </div>
</div>

  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
