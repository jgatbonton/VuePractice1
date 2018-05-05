<template>
  <div class="about">
    <h1>Hello {{ their_name }}, This is my Vue Practice</h1>
    <p>This framework is pretty cool.</p>
  </div>
</template>

<script>
  export default {
    name: 'Skills',
    data() {
      return {
          their_name: this.$route.params.name
      }
    }
  }
</script>