<template>
  <div class="google-maps-page">
    <div class="row">
      <div class="col-md-12">
        <vuestic-widget
          class="google-maps-page__widget"
          headerText="Google Maps"
        >
          <google-map/>
        </vuestic-widget>
      </div>
    </div>
  </div>
</template>

<script>
import GoogleMap from './GoogleMap'

export default {
  name: 'google-maps-page',
  components: {
    GoogleMap
  }
}
</script>

<style lang="scss">
 .google-maps-page{
   &__widget {
     height: 70vh;
   }
 }
</style>
