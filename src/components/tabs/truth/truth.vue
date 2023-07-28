<script>
export default {
  name: "truth",
  components: {
  },
  data() {
    return {
      isUnlocked: true
    };
  },
  computed: {
    grid() {
    }
  },
  methods: {
    update() {
      this.isUnlocked = true
    },
  }
};
</script>

<template>
  <div class="o-tab-btn--truth">
    <div v-if="isUnlocked">
      Discover the truth.
    </div>
    </div>
</template>

<style scoped>

</style>
