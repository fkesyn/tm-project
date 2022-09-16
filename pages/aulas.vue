<template>
  <section>
    <div class="block">
      <h1 class="title">Locais de aulas</h1>
    </div>
    <div class="columns">
      <div class="column">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img
                :src="require('@/assets/images/theview.jpg')"
                alt="Placeholder image"
              />
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left">
                <figure class="image is-48x48">
                  <img
                    :src="require('@/assets/images/Cais_de_Gaia.jpg')"
                    alt="Placeholder image"
                  />
                </figure>
              </div>
              <div class="media-content">
                <p class="title is-4">The View</p>
                <p class="subtitle is-6">
                  <a href="https://www.instagram.com/the_view_loungebar/"
                    >@the_view_loungebar</a
                  >
                </p>
              </div>
            </div>

            <div class="content">
              Bar dedicado a cocktails e Musica Avenida Ramos Pinto ao Cais de
              Gaia Loja 340 a 360
            </div>
          </div>
        </div>
      </div>
      <div class="column">
        <div class="card">
          <div class="card-image">
            <figure class="image is-4by3">
              <img
                :src="require('@/assets/images/aguassantas.jpg')"
                alt="Placeholder image"
              />
            </figure>
          </div>
          <div class="card-content">
            <div class="media">
              <div class="media-left">
                <figure class="image is-48x48">
                  <img
                    src="https://bulma.io/images/placeholders/96x96.png"
                    alt="Placeholder image"
                  />
                </figure>
              </div>
              <div class="media-content">
                <p class="title is-4">Algures em Aguas Santas</p>
                <p class="subtitle is-6">
                  Não sei onde é isto, é so um exemplo
                </p>
              </div>
            </div>

            <div class="content">Oh menino eu sei lá se sao os chineses</div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'AulasPage',
}
</script>
