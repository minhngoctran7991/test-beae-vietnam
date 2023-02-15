<template>
  <div class="max-w-[1200px] mx-auto">
    <tab-test />
    <gallery-image />
  </div>
</template>
<script>
export default {
  components: {
    TabTest: () => import('./components/TabTest'),
    GalleryImage: () => import('./components/GalleryImage'),
  },
}
</script>