<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <h1 style="font-size:50px" >Porta400</h1>

    <div class="home-links">
      <p><span>Categories</span> <span style="margin-left:70px">Year</span></p>
      <p><span>photography,yellow</span> <span style="margin-left:70px">2019</span></p>
    </div>
    <g-image  alt="Example image" style="width:750px;margin-top:50px" src="https://gridsome-forestry.netlify.app/assets/static/markus-spiske-516263-unsplash.2665e34.5fc4651133067e67284df56f3d81be2d.jpg"/>
    <p>Copyright © 2021</p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
