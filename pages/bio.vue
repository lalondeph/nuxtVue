<template>
  <div class="container">
    <div>
      <h1 class="title">
          <PhilLogoSm /> 
          Philip Lalonde
      </h1>
      <div class="links">
        <a
          href="../"
          target="_blank"
          rel="noopener noreferrer"
          class="button--red"
        >
          Home
        </a>
        <a
          href="https://github.com/lalondeph/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a>
        <a
          href="https://www.linkedin.com/in/philip-lalonde/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--blue"
        >
          LinkedIn
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>