<template>
  <b-carousel>
    <b-carousel-item v-for="(carousel, i) in carousels" :key="i">
      <section :class="`hero is-medium is-${carousel.color}`">
        <div class="hero-body has-text-centered">
          <h1 class="title">{{ carousel.text }}</h1>
          <img :src="require('@/assets/images/'+ carousel.img)" alt="Placeholder image" />
        </div>
      </section>
    </b-carousel-item>
  </b-carousel>
</template>

<script>
export default {
  name: 'EventosPage',
  data() {
    return {
      carousels: [
        {
          text: 'Dance In Porto',
          color: 'primary',
          img: 'Danceinporto.jpg',
        },
        {
          text: 'Outros a anunciar no The View',
          color: 'info',
          img: 'Cais_de_Gaia.jpg',
        },
        {
          text: 'A anunciar na Povoa',
          color: 'success',
          img: 'povoa.jpg',
        },
      ],
    }
  },
}
</script>
