<template>
    <nav class="navbar navbar-expand-lg py-3">
        <div class="container">
          <a class="navbar-brand" href="#">
            <img src="/logo.svg" alt="" class="img-fluid logo">
          </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mx-auto mb-2 mb-lg-0">
        
              <li class="nav-item me-2 " v-for="list in navList">
                <a class="nav-link text-dark" :href="`#${list.link}`">{{list.name}}</a>
              </li>
            </ul>
        
          </div>
        </div>
      </nav>
</template>
  
<script>
  
export default {
    data() {
        return {
            navList: [
                {
                    name: 'Home',
                    link: 'home',
                },
                {
                    name: 'About Us',
                    link: 'about-us',
                },
                {
                    name: 'Services',
                    link: 'services',
                },
                {
                    name: 'Contact Us',
                    link: 'contact-us',
                }
            ]
        }
    }
}


</script>
  
<style scoped>
.logo {
    width: 80px;
}
</style>
  