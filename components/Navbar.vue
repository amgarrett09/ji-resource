<template>
  <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      JI Resource
      <button class="navbar-burger burger" @click="toggleMenu">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </button>
    </div>
    <div class="navbar-menu" :class="{ 'is-active': menuOpen }">
      <div class="navbar-start">
        <nuxt-link to="/">
          <span class="navbar-item">Home</span>
        </nuxt-link>
        <nuxt-link to="/lessons">
          <span class="navbar-item">Lessons</span>
        </nuxt-link>
      </div>
      <div class="navbar-end"></div>
    </div>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      menuOpen: false
    }
  },
  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen
    }
  }
}
</script>

<style scoped>
.navbar {
  background-color: #e02f2f;
  font-size: 1.2rem;
  width: 100%;
}
.navbar-menu {
  background-color: #e02f2f;
}
@media (max-width: 1023px) {
  .navbar-menu {
    position: absolute;
    background-color: hsl(0, 0%, 20%);
    z-index: 100;
    width: 100%;
  }
}
.navbar * {
  color: white;
}
.navbar-burger {
  background: transparent;
  border: none;
}
</style>
