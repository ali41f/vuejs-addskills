<template>
  <div class="about">
    <h1>Hello , I'm Ali Rehman</h1>
    <p>
      This is minimal vuejs app where you can add skills.
    </p>
  </div>
</template>
<script>
export default {
  name: "about",
  data() {
    return {
      their_name: this.$route.params.name
    };
  }
};
</script>