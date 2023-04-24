<template>
  <div class="container">
    <div class="section links">
      <Nav />
    </div>
    <div class="section tribute">
      <!-- CONTENT START -->
      <h1 class="title">In Loving Memory</h1>

      <p>
      For Google Maps Directions Use the following Link : <br/><br/>  <a href="https://goo.gl/maps/F2ytRutJVrPzuTmHA" target="_blank">Click Here For Directions To The Funeral</a>
      </p>
      <img height="292" src="~/assets/frontimage.jpeg" alt="In loving memory" />
      <div class="subtitle"><div class="name">{{ $config.name }}</div>{{ $config.dates }}</div>

      <p>
      Download PDF Version of the Eulogy : <br/><br/>  <a href="https://res.cloudinary.com/hackit-africa/image/upload/v1682346749/elizabeth_wamitu_programme_1_1.pdf" target="_blank">Click Here To Download</a>
      </p>
      <!-- CONTENT END -->
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">

</style>
