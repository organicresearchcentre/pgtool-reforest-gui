<script>
module.exports = {
  name: "top",
  data() {
    return {
    }
  },
}
</script>

<template>
  <div class="header row no-gutters h-90">
    <div class="col-9 pgtitle">
      <router-link to="/" class="nav-link text-white text-left">
        <h3 class="title"><strong>REFOREST Public Goods Tool</strong></h3>
      </router-link>
    </div>
    <div class="col-3 no-gutters logos">
        <div class="text-center"><img src="img/reforest-logo.png" class="logo"></div>
        <div class="text-center"><img src="img/orc-logo-v2.png" class="logo"></div>
    </div>
  </div>
</template>