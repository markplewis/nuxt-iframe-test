<template>
  <button class="c-button" type="button">
    <span class="c-button__text">{{ text }}</span>
  </button>
</template>

<script>
  export default {
    props: {
      text: {
        default: "Button",
        type: String
      }
    }
  }
</script>
