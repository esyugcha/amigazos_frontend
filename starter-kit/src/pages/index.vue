<script setup>
import ThumbsCarousel from "@/components/ThumbsCarousel.vue";
import GroupImage from "@/components/GroupImage.vue";
</script>
<template>
  <div>
    <VCol
      cols="12"
      md="12"
      class="pa-0"
    >
      <ThumbsCarousel />
    </VCol>
    <VCard
      class="mb-6 mt-6"
    >
      <GroupImage />
    </VCard>
  </div>
</template>
