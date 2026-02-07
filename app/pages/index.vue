<template>
  <main class="page">
    <section
      class="splash"
      aria-label="Splashscreen"
    >
      <p class="eyebrow">
        Quick Template to start
      </p>
      <h1 class="title">
        NuxtUI Sandbox
      </h1>
      <p class="subtitle">
        Lightweight Nuxt 4 template for static GitHub Pages deployments.
      </p>
      <p class="credit">
        by Marc Frankfurter
      </p>
    </section>
  </main>
</template>

<style scoped>
.page {
  min-height: 100vh;
  display: grid;
  place-items: center;
  background: linear-gradient(140deg, #0f172a 0%, #1e293b 55%, #334155 100%);
  color: #e2e8f0;
}

.splash {
  text-align: center;
  padding: 2rem;
  width: min(760px, 92vw);
}

.eyebrow {
  margin: 0;
  font-size: 0.78rem;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: #93c5fd;
}

.title {
  margin: 0.75rem 0 0;
  font-size: clamp(2rem, 4.4vw, 3.2rem);
  line-height: 1.05;
  color: #f8fafc;
}

.subtitle {
  margin: 0.9rem 0 0;
  font-size: 1rem;
  color: #cbd5e1;
}

.credit {
  margin: 1.1rem 0 0;
  font-size: 0.78rem;
  letter-spacing: 0.04em;
  color: #cbd5e199;
}
</style>
