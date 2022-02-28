<template>
  <div class="t-select">
    <select name="some" id="some">
      <option value="">{{ text }}</option>
    </select>
  </div>
</template>

<script>
export default {
  name: 'TSelect',

  props: {
    text: {
      type: String,
      default: 'text'
    }
  }
}
</script>

<style></style>
