<script></script>

<template>
  <div class="sideBar">
    <img src="../assets/test_char.png" height="175" id="characterImage" />
    <h1>test</h1>
    <h1>test</h1>

    <div class="stat">
      <p class="statLabel">Health</p>
      <div class="progressBar">
        <div class="bar" id="healthBar"></div>
      </div>
    </div>
    <div class="stat">
      <p class="statLabel">Hunger</p>
      <div class="progressBar">
        <div class="bar" id="hungerBar"></div>
      </div>
    </div>
    <div class="stat">
      <p class="statLabel">Thirst</p>
      <div class="progressBar">
        <div class="bar" id="thirstBar"></div>
      </div>
    </div>
    <div class="stat">
      <p class="statLabel">Stress</p>
      <div class="progressBar">
        <div class="bar" id="stressBar"></div>
      </div>
    </div>
    <div class="stat">
      <p class="statLabel">Control</p>
      <div class="progressBar">
        <div class="bar" id="controlBar"></div>
      </div>
    </div>

    <div id="buttons">
      <button class="sideBarButton">Map</button>
      <button class="sideBarButton">Journal</button>
      <button class="sideBarButton">Help</button>
      <button class="sideBarButton">Save</button>
    </div>
  </div>
  <RouterLink to="/">home</RouterLink>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<style>
.sideBar {
  float: left;
  height: 100%;
  width: 25%;
  border-right: 2px solid var(--color-text);
}

#characterImage {
  margin-bottom: 2em;
}

.stat {
  margin-top: 1em;
}

.statLabel {
  font-size: 1.4em;
}

.progressBar {
  margin: auto;
  margin-top: 0.25em;
  width: 90%;
  background-color: grey;
}

.bar {
  height: 2px;
  background-color: red;
}

#healthBar {
  width: 100%;
}

#hungerBar {
  width: 90%;
}

#thirstBar {
  width: 90%;
}

#stressBar {
  width: 10%;
}

#controlBar {
  width: 80%;
}

.sideBarButton {
  border: 2px solid var(--color-text);
  padding: 0.5em;
  width: 50%;
  text-align: center;
  background-color: transparent;
  color: var(--color-text);
  font-size: 1.3em;
}

#buttons {
  margin-top: 2em;
}
</style>

<!-- run once I guess -->
<!--
<script setup>
import { createMemoryHistory, createRouter } from 'vue-router'

import HomeView from './HomeView.vue'

const routes = [
  { path: '/', component: HomeView },
]

const router = createRouter({
  history: createMemoryHistory(),
  routes,
})
</script>
-->
