<script setup>
  const project_name = 'Project T'
</script>

<template>
  <h1 class="headline">Welcome to {{ project_name }}</h1>
  
  <RouterLink to="/newGame">game</RouterLink>
  <br />
  <button class="link">New Game</button>
  <button class="link">Load Save</button>
</template>

<style>
.headline {
  color: red;
  font-weight: bold;
  font-size: 4em;
  margin-top: 5rem;
}

.link {
  color: hsla(160, 100%, 37%, 1);
  background: transparent;
  border: none;
  margin: 7rem;
  font-size: 2em;
}

.link:hover {
  background-color: hsla(160, 100%, 37%, 1);
  color: white;
}
</style>
