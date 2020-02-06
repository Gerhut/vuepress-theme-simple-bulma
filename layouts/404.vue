<template>
  <div>
    <main class="hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">404 Not Found</h1>
          <h2><a href="/">Take me home</a></h2>
        </div>
      </div>
    </main>
    <footer v-if="$themeConfig.footer" class="footer">
      <div class="content has-text-centered">
        <p v-html="$themeConfig.footer"/>
      </div>
    </footer>
  </div>
</template>
