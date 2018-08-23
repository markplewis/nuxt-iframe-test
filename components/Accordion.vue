<template>
  <div class="c-accordion">
    <ul class="c-accordion__list">
      <li class="c-accordion__item">
        <div class="c-accordion__item-container">
          <a href="#" class="c-accordion__item-link">Item 1</a>
          <simple-button text="X" />
        </div>
      </li>
      <li class="c-accordion__item">
        <div class="c-accordion__item-container">
          <a href="#" class="c-accordion__item-link">Item 2</a>
          <simple-button text="X" />
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
  import SimpleButton from "~/components/Button.vue";

  export default {
    components: {
      SimpleButton
    }
  }
</script>
