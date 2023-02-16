<template>
    <!-- Start Header  -->
    <header class="mb-5">
      <nav-bar/>
    </header>
    <!-- End Header  -->



    <!-- Start Landing -->

    <section class="landing my-5 py-5">

       <div class="container">

        <div class="row ">
          <div class="col-md-6">
              <h1 class="mb-3 fw-bold lh-sm">We are Digital 
                <br>
                Agency.</h1>

                <p class="text-muted mb-4">
                  Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
                </p>

                <button class="btn btn-dark rounded-pill px-4 py-2">Get Started</button>
          </div>
          <div class="col-md-6">

          </div>
        </div>


       </div>


      
    </section>

    <!-- End Landing  -->

</template>

<script>
import NavBar from './components/NavBar.vue';

export default {
  components: {
    NavBar
  }
}

</script>

<style>
@import '../public/css/bootstrap.css';
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100&display=swap');

* {
  font-family: 'Poppins', sans-serif !important;
}
</style>
