<template>
  <HeaderPage />


  <div class="canal-container">
    <div class="top-heading">
      <div class="">
        <div class="">
          <p>Rajasthan</p>
          <!-- <p v-if="selectedDistrict">>> {{ selectedDistrict }}</p>
        <p v-if="selectedBasin">>> {{ selectedBasin }}</p>
        <p v-if="selectedStation">>> {{ selectedStation }}</p>
        <p v-if="selectedYear"> | </p>
        <p v-if="selectedYear">Year- {{ selectedYear }}</p> -->
        </div>
      </div>
      <div class="">
        <div class="pageheading">
          Canal Data
        </div>
      </div>
    </div>


    <div class="canal-map-container">
      <div class="left-map-container">
        <div class="dataviewcanalbtn">
          <h2 style="cursor: pointer;">IRRIGATION SYSTEM</h2>
        </div>

        <div class="lefttreemenuCanal">
          <div class="containerdiv">
            <div id="treeCanal" class="layer-wrap" style="height:545px; box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.20);">
            </div>
          </div>
        </div>
      </div>

      <div class="right-map-container">
        <div class="canalbox">
          <div class="histcardrain boxbg">
            <p class="des">Canal Network (km)</p>
            <h3>"hgdgf"</h3>
          </div>

          <div class="histcardrain boxbg">
            <p class="des">CCA (lac ha)</p>
            <h3>hgdfdfd</h3>
          </div>

          <div class="histcardrain boxbg">
            <p class="des"> Water Allocation (mcm) </p>
            <h3>Total: </h3>
            <div>
              <span>Irrigation: </span><br />
              <span>Drinking: </span>
            </div>
          </div>

          <div class="histcardrain boxbg">
            <p class="des"> Water Release (mcm) </p>
            <h3>hhhh</h3>
          </div>
        </div>
  
        <div class="canalmapdiv">
          <div id="canalMapView" class="cardn basic1 mapDiv" style="width:100%; height: 100%">
            map here
          </div>
        </div>

      </div>
    </div>

    <div class="canal-details-container">
      <div class="cardn">

      </div>
      <div class="cardn">

      </div>
      <div class="cardn">

      </div>
    </div>

  </div>

</template>

<script>

import HeaderPage from "./HeaderPage.vue";

export default {
  name: 'HomePage',
  components: {
    HeaderPage
  },
  props: {
    msg: String
  }
}
</script>
