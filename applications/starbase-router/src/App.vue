<template>
  <div id="app">
    <h3>StarBase router</h3>
    <h4>
      <router-link class="router-link" to="/data/people">Meet the Characters</router-link> |
      <router-link class="router-link" to="/data/planets">Explore the Planets</router-link>
    </h4>
    <router-view> </router-view>
  </div>
</template>
