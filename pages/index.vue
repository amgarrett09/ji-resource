<template>
  <div class="index__container">
    <navbar />
    <main>
      <section>
        <div class="landing-text">
          <h1 class="title is-1">
            Have you ever wondered why there are twelve tones in an octave?
          </h1>
          <p>
            Or perhaps you have noticed that no matter how well you tune your
            guitar, some chords still sound out-of-tune...
          </p>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: {
    Navbar
  }
}
</script>

<style scoped>
main {
  background-color: #e02f2f;
  min-height: 100vh;
}
.landing-text {
  text-align: center;
  margin: 0 auto;
  max-width: 50%;
  position: relative;
  top: 100px;
}
.landing-text * {
  color: white;
}
.landing-text p {
  font-size: 1.5rem;
}
.index__container {
  max-width: 80%;
  margin: 0 auto;
}

@media (max-width: 1023px) {
  .index__container {
    max-width: 100%;
  }
}
</style>
