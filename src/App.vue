<template>
  <div class="main">
    <router-view></router-view>
  </div>
</template>

<script lang="ts">
  import { defineComponent } from "vue";
  import { RouterView } from "vue-router";

  const Component = defineComponent({
    name: "App",
    components: {
      RouterView,
    },
    setup(props) {
      return {};
    },
  });

  export default Component;
</script>


<style lang="scss" scoped>
</style>