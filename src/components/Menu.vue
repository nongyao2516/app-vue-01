<template>

  <div id="nav">
    <div class="container-fluid">
    <header class="  d-flex flex-wrap align-items-center justify-content-center justify-content-md-between py-2 mb-4 border-bottom bg-body-secondary  fixed-top">
      <div class="col-md-3 mb-2 mb-md-0">
        <a href="/" class="d-inline-flex link-body-emphasis text-decoration-none">
          <svg class="bi" width="40" height="32" role="img" aria-label="Bootstrap"><use xlink:href="#bootstrap"></use></svg>
        </a>
      </div>

      <ul class="nav col-12 col-md-auto mb-2 justify-content-center mb-md-0">
        <li><router-link to="/" class="nav-link px-2 ">Home</router-link></li>
        <li><router-link to="/product"  class="nav-link px-2">Products</router-link></li>
        <li><router-link to="/member"  class="nav-link px-2">Member</router-link></li>
        <li><router-link to="/about"  class="nav-link px-2">About</router-link></li>
      </ul>

      <div class="col-md-3 text-end">
        <router-link to="/Login"> <button type="button" class="btn btn-outline-primary me-2">Login</button> </router-link> 
        <button type="button" class="btn btn-primary">Sign-up</button>
      </div>
    </header>
  </div>

</div>
<div class="" style="padding-top: 100px;"></div>





  </template>
  
  <script>
  export default {
      neme: 'Menu'
  }
  </script>
  
  <style>

</style>