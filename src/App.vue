<!-- <script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script> -->

<template>
<div class="container-fluid">
  <div class="container">

    <section id="home-head">
      <!-- INICIO ROW -->
      <div class="row mt-5">
        <div class="col-sm-7 mb-3 mb-sm-0">
          <div class="card cristal-2 text-end h-100">
            <div class="card-body">
              <h5 class="card-title">Checklist de seguridad WP</h5>
              <i class="bi bi-card-checklist display-1 float-start mx-4" role="img" aria-label="Checklist"></i>
              <span class="display-6">
                Sigue este checklist y verifiraca los basicos de seguridad para sitio wordpress.
              </span>
              <div class="d-grid gap-2 col-6 mx-auto mt-5">
                <button class="btn btn-lg btn-cristal-purple" type="button">Checklist <i class="bi bi-check-all"></i></button>
              </div>
                          
            </div>
          </div>
        </div>
        <div class="col-sm-5">
          <div class="card cristal-1 h-100 text-center">
            <div class="card-body">
              <h5 class="card-title">Chequea rápido de mi WP</h5>
              <p class="card-text mt-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cupiditate, quisquam ipsa aliquid deserunt dolorum atque at labore placeat, iste officia repellendus dicta laudantium iusto voluptas ipsam asperiores minima pariatur id.</p>
              <div class="py-6">
                <form action="">
                  <div class="form-floating mt-4 mb-3">
                    <input type="url" class="form-control cristal text-center" id="floatingInput" placeholder="Tu dominio WP">
                    <label for="floatingInput">Tu dominio WP</label>
                  </div>
                </form>
              </div>
                <div class="d-grid gap-2 col-6 mx-auto mt-1">
                  <button class="btn btn-lg btn-cristal-purple" type="button">Chequea mi WP <i class="bi bi-wordpress"></i></button>
                </div>
            </div>
          </div>
        </div>
        </div>
        <!-- FIN ROw -->
    </section>


    <!-- MENU -->

    <nav class="navbar navbar-expand-lg bg-body-tertiary sticky-top navbar-light bg-light my-4">
      <div class="container-fluid">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mx-auto text-center nav-fill w-100">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"> <i class="bi bi-house-heart"></i>  Inicio</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="bi bi-wordpress"></i> Checklist</a>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#"><i class="bi bi-search-heart"></i> Chequea</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#"><i class="bi bi-bandaid"></i> Recursos</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Acerca de <i class="bi bi-patch-question"></i> </a>
            </li>
          </ul>
          <!-- <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form> -->
        </div>
      </div>
    </nav>
    <!-- FIN MENU  -->

    <!-- SIGNAL  -->
    <section id="signal-banner">
      <div class="container">

        <div class="card cristal-blue mt-4 mb-4 text-light">
          <h5 class="card-header">¿Necesitas ayuda</h5>
          <div class="card-body">
            <h5 class="card-title">Intenta con nuestra linea de ayuda por signal</h5>
            <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Cum iste natus porro corrupti ex cumque harum perspiciatis similique nobis, omnis debitis saepe pariatur doloremque culpa molestias perferendis minima labore deserunt!</p>
            
            <div class="d-grid gap-2">
              <a href="#" class="btn btn-dark">Contactanos en signal <i class="bi bi-signal"></i></a>
            </div>
          </div>
        </div>

      </div>
    </section>
    <!-- FIN SIGNAL  -->

    <!-- BLOG -->
    <div class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col">
        <div class="card h-100">
          <img src="https://picsum.photos/id/237/200/300?blur" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="https://picsum.photos/id/237/200/300?blur" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="https://picsum.photos/id/237/200/300?blur" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="https://picsum.photos/id/237/200/300?blur" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Card title</h5>
            <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 mins ago</small>
          </div>
        </div>
      </div>
    </div>
    <!-- Fin BLOG  -->

    
    <div class="container">
      <footer class="d-flex flex-wrap justify-content-between align-items-center py-3 my-4 border-top">
        <div class="col-md-6 d-flex align-items-center">
          <a href="/" class="mb-3 me-2 mb-md-0 text-muted text-decoration-none lh-1">
            <svg class="bi" width="30" height="24"><use xlink:href="#bootstrap"></use></svg>
          </a>
          <span class="mb-3 mb-md-0 text-muted"><i class="bi bi-wordpress"></i> - <i class="bi bi-cc-circle"></i> 2023 Un proyecto con apoyo de ...</span>
        </div>

        <ul class="nav col-md-6 justify-content-end list-unstyled d-flex">
          <li class="ms-3"><a class="text-muted" href="#"><i class="bi bi-twitter"></i></a></li>
          <li class="ms-3"><a class="text-muted" href="#"><i class="bi bi-instagram"></i></a></li>
          <li class="ms-3"><a class="text-muted" href="#"><i class="bi bi-signal"></i></a></li>
        </ul>
      </footer>
    </div>
  
  </div>
</div>
</template>

<style>

</style>



<!-- <template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template> -->

<style scoped>




</style>
