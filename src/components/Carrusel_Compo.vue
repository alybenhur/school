<template>
  <v-carousel
    height="400"
    show-arrows="hover"
    cycle
    hide-delimiter-background
  >
    <v-carousel-item
      v-for="(slide) in slides" :key="i"
       :src="slide"
        cover
    >
    
    </v-carousel-item>
  </v-carousel>
</template>

<script setup>
  const colors = [
    'indigo',
    'warning',
    'pink darken-2',
    'red lighten-1',
    'deep-purple accent-4',
  ]
  const slides = [
    'https://cdn.vuetifyjs.com/images/cards/docks.jpg',
    'https://cdn.vuetifyjs.com/images/cards/hotel.jpg',
    'https://cdn.vuetifyjs.com/images/cards/sunshine.jpg',
  ]
</script>