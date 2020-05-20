<template>
  <div class="container">
    <div class="content">
      <h1 class="title">Hello, my name is Erkan.</h1>

      <h2 class="subtitle">I am a Front End Developer living in Istanbul, TR.</h2>

      <div class="links">
        <a href="https://github.com/erkansivas35"
           target="_blank"
           class="button--grey">
          GitHub
        </a>
        <a href="https://www.linkedin.com/in/erkansivas35/"
           target="_blank"
           class="button--blue">
          LinkedIn
        </a>
        <a href="https://twitter.com/erkansivas35"
           target="_blank"
           class="button--light-blue">
          Twitter
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Homepage'
}
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
.content {
  width: 100%;
  padding: 48px 24px;
  background-color: rgba(235, 235, 235, 0.4);
}

.title {
  font-family: 'Noto Sans', sans-serif;
  font-weight: 900;
  color: #35495e;
  letter-spacing: 1px;
  font-weight: 300;
  font-size: 4rem;
  padding-bottom: 16px;
}

@media (max-width: 992px) {
  .title {
    font-size: 3rem;
  }
}

.subtitle {
  font-family: 'Noto Sans', sans-serif;
  color: rgba(53, 73, 94, 0.9);
  font-weight: 300;
  font-size: 1.5rem;
  letter-spacing: -0.5;
  padding-bottom: 16px;
}

.links {
  padding-top: 16px;
}

.links a {
  margin-right: 8px;
  margin-bottom: 8px;
}

.links a:last-child {
  margin-right: 0;
}

.links a {
  transition: 0.3s;
}
</style>
