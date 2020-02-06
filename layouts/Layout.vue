<template>
  <div>
    <header v-if="$frontmatter.hero" class="hero" :class="$frontmatter.hero">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">{{ $site.title }}</h1>
          <h2>{{ $site.description }}</h2>
        </div>
      </div>
    </header>
    <main class="section">
      <div class="container">
        <div class="content">
          <Content/>
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
