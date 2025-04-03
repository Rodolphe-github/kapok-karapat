<template>
  <div class="container">
    <h1 class="title">Bienvenue sur le site officiel</h1>
    <p class="subtitle">Choisissez un univers</p>

    <div class="links">
      <NuxtLink to="/kapok" class="button">Le Kapok</NuxtLink>
      <NuxtLink to="/karapat" class="button">Le Karapat</NuxtLink>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
  text-align: center;
  padding: 2rem;
}
.title {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}
.subtitle {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}
.links {
  display: flex;
  gap: 2rem;
}
.button {
  padding: 1rem 2rem;
  background-color: #333;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  transition: background-color 0.2s ease;
}
.button:hover {
  background-color: #555;
}
</style>
