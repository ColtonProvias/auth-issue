<template>
  <section class="container">
    <div>
      <nuxt-link to="/protected">This link generates a redirect.</nuxt-link>
    </div>
    <div>
      <a href="/protected">This link does not generate a redirect.</a>
    </div>
  </section>
</template>
