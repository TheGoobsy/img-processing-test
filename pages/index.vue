<template>
  <div>
    <!--<div class="container">
      <img src="/waterfall.jpg" alt="waterfall" />
      <img src="/forest.jpg" alt="forest" />
      <img src="/hills.jpg" alt="hills" />
      <img src="/forest-hill.jpg" alt="forest-hill" />
      <img src="/island.jpg" alt="island" />
      <img src="/beach.jpg" alt="beach" />
      <img src="/lake.jpg" alt="lake" />
    </div>-->

    <div class="container">
      <SfImage src="/waterfall.jpg" alt="waterfall" width="20px" height="20px"/>
      <SfImage src="/forest.jpg" alt="forest" />
      <SfImage src="/hills.jpg" alt="hills" />
      <SfImage src="/forest-hill.jpg" alt="forest-hill" />
      <SfImage src="/island.jpg" alt="island" />
      <SfImage src="/beach.jpg" alt="beach" />
      <SfImage src="/lake.jpg" alt="lake" />
    </div>

  </div>
</template>
<script type="module">
import { SfImage } from "@storefront-ui/vue";

export default {

  components: {
    SfImage
  }
}
</script>
<style >


.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
  max-width: 1180px;
}.container img {
  display: block;
  height: auto;
  max-width: 100%;
  object-fit: contain;
  margin-top: 4rem;
}
</style>