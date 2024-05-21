<template>
  <div>
    <nuxt />

    <div class="cf-turnstile" data-sitekey="0x4AAAAAAAasfIOromUWax2U" data-callback="javascriptCallback"></div>
  </div>
</template>

<style>
html {
  font-family: 'Noto Sans', sans-serif;
  font-weight: 300;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

html,
body {
  background-color: rgba(223, 223, 223, 0.15);
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

.button--blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #2a77b5;
  color: #2a77b5;
  text-decoration: none;
  padding: 10px 30px;
}

.button--blue:hover {
  color: #fff;
  background-color: #2a77b5;
}

.button--light-blue {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3ca1f2;
  color: #3ca1f2;
  text-decoration: none;
  padding: 10px 30px;
}

.button--light-blue:hover {
  color: #fff;
  background-color: #3ca1f2;
}
</style>
