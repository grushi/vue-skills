<template>
  <div class="about">
      <h3>Hello {{their_name}}, this about page</h3>
  </div>
</template>

<script>
export default {
  name: "Skills",
  data() {
    return {
      their_name:this.$route.params.name
    }
  },
}
</script>