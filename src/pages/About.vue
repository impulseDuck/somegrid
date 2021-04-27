<template>
  <Layout>
    <h1>Say hi!</h1>
    <p>
      Leave me a note with any questions you might have, I'll get back to you as soon as possible.
    </p>
    <div style="display:flex">
      <div style="flex:1">
        <p>Your name</p>
        <input type="text">
      </div>
      <div style="flex:1">
        <p>Your email</p>
        <input type="email">
      </div>
    </div>
    <div style="margin-bottom:20px">
      <p>Message</p>
      <input type="text" style="width:530px">
    </div>
    <button style="backgroundColor:black;color:white;width:200px;padding:10px 0">Submit form</button>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "About us",
  },
};
</script>
