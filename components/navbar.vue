<template>
  <div class="mb-5">
    <b-navbar toggleable="md" type="dark" variant="info">
      <b-navbar-brand href="#">CRUD Nuxt</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item href="/">Inicio</b-nav-item>
          <b-nav-item href="/blog">Blog</b-nav-item>
          <b-nav-item href="/vuex">Vuex</b-nav-item>
          <b-nav-item href="/contacto">Contacto</b-nav-item>
        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input size="sm" class="mr-sm-2" placeholder="Search"></b-form-input>
            <b-button size="sm" class="my-2 my-sm-0" type="submit">Buscar</b-button>
          </b-nav-form>
        </b-navbar-nav>

      </b-collapse>
    </b-navbar>
  </div>
</template>
