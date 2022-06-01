<template>
  <div class="slideshow">
    <div class="slideshow__content">
      <div class="slideshow__slides">
        <figure class="slideshow__slide">
          <img class="slideshow__img" />
          <span>{{ query }}</span>
        </figure>
      </div>

      <div class="slideshow__dots">
        <button class="slideshow__dot"></button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentImage: "",
      themePictures: [],
    };
  },

  props: {
    query: String,
  },

  methods: {
    async fetchImage() {
      const url = `https://api.unsplash.com/search/photos?query=${this.description}&client_id=TWlHBsRI4XqG8aWaT_ZleTAUvRK88x0rvMoCN_THO5g`;
      const response = await fetch(url);
      const { results } = await response.json();
      this.image = results.urls.regular;
    },
  },
};
</script>
