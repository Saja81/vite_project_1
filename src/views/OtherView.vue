<script>
import OtherThings from "../components/OtherThings.vue";
import PropsComponent from "../components/PropsComponent.vue";

export default {
  components: {
    OtherThings,
    PropsComponent,
  },
};
</script>

<template>
  <OtherThings />
  <PropsComponent test="Sandra, du är grym!" />
</template>
