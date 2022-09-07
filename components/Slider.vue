<template>
  <div class="swiper mySwiper">
    <div class="swiper-wrapper">
      <div class="swiper-slide">Slide 1</div>
      <div class="swiper-slide">Slide 2</div>
      <div class="swiper-slide">Slide 3</div>
      <div class="swiper-slide">Slide 4</div>
      <div class="swiper-slide">Slide 5</div>
      <div class="swiper-slide">Slide 6</div>
      <div class="swiper-slide">Slide 7</div>
      <div class="swiper-slide">Slide 8</div>
      <div class="swiper-slide">Slide 9</div>
    </div>
  </div>
</template>

<script>
  import { Swiper, Autoplay } from 'swiper';
  import 'swiper/swiper-bundle.min.css'
  export default {
    mounted() {
      const swiper = new Swiper('.swiper', {
        loop: false,
        grabCursor: true,
        modules: [Autoplay],
        autoplay: {
          delay: 1500,
        },
      })
    },
  }
</script>

<style>

</style>
