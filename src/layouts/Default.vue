<template>
  <div class="layout">
    <header class="header">
      <img src="https://gridsome-forestry.netlify.app/assets/img/logo.332701b7.svg" alt="" width="50">
      <nav class="nav">
        <g-link class="nav__link" to="/">Journal</g-link>
        <g-link class="nav__link" to="/about/">Say Hi!</g-link>
      </nav>
    </header>
    <slot/>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
  font-family: -apple-system,system-ui,BlinkMacSystemFont,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
}

.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
  height: 80px;
}

.nav__link {
  margin-left: 20px;
}
</style>
