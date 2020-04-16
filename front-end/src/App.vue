<template>
<div id="app">
  <div class="header">
    <router-link to="/">
      <div class="logo">
        <img src="https://cdn.pixabay.com/photo/2013/07/13/09/47/laurel-wreath-156019__340.png" style="width:100px;height:100px; margin-right: 50px;">
      </div>
    </router-link>
    <div class="title">
      <h1>Contest Me!</h1>
    </div>
    <img src="https://cdn.pixabay.com/photo/2013/07/13/09/47/laurel-wreath-156019__340.png" style="width:100px;height:100px; margin-left: 50px;">
  </div>
  <div class="content">
    <router-view />
  </div>
  <div class="footer">
    <router-link to="/">Home</router-link> |
    <router-link to="/enter">Enter Contest</router-link> |
    <router-link to="/about">About</router-link> |
    <a href="https://github.com/wallace128/contest.git">GitHub</a> </div>
</div>
</template>

<style>
html {
  box-sizing: border-box;
}

body {
  font-family: 'Montserrat', sans-serif;
  font-size: 16px;
  background: #fff;
  padding: 0px;
  margin: 0px;
}

/* Header */
.header {
  display: flex;
  padding: 10px 100px 0px 100px;
  background-color: #c0ded9;
  color: #00000;
}


.title {
  margin-top: 5px;
}

.title h1 {
  font-size: 30px;
}

.content {
  padding: 20px 100px;
  min-height: 500px;
}

/* Footer */
.footer {
  height: 50px;
  padding: 20px 100px 0px 100px;
  background: #e3e3e3;
  font-size: 12px;
}

.footer a {
  color: #000;
}

h1 {
  font-size: 20px;
}

h2 {
  font-size: 14px;
}
</style>
