<template>
    <div class="box">
      <div class="columns">
<div class="column is-6 contentheight">
<vPlan></vPlan>
</div>

<div class="column is-6">
  <div class="box contentheight">d</div>
</div>
</div>
<div class="columns">
  <div class="column is-6">
<div class="box contentheight">d</div>
  </div>
  <div class="column is-6">
<div class="box contentheight">d</div>
  </div>
    </div>
</div>
</template>
<script>
  import vPlan from './vPlan'
  export default {
    components: {
      vPlan
    }
  }
</script>
<style scoped>
.contentheight{
  height: 280px
}
</style>

