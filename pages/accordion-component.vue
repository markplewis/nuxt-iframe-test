<template>
  <div>
    <p>Accordion component:</p>
    <accordion/>
  </div>
</template>

<script>
  import Accordion from "~/components/Accordion.vue";

  export default {
    components: {
      Accordion
    }
  }
</script>

<style lang="scss">
  @import "assets/stylesheets/base";
  @import "assets/stylesheets/components.accordion";
  @import "assets/stylesheets/components.button";

  @media (min-width: 600px) {}
</style>

