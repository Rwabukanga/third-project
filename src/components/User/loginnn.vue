<template>
  <section class="container min-container py-md-5 mt-4">
  <div class="card-panel p-sm-5 position-relative">
    <div class="text-center">
      <img src="https://raw.githubusercontent.com/solodev/input-fields-with-fontawesome/master/images/lunar-xp-logo.png" alt="Logo" class="img-fluid w-50">
      <h1 class="h2 mt-5">Welcome, Explorer!</h1>
    </div>
    <form id="loginForm" class="mt-5">
      <p class="small mb-2 text-scarlet"></p>
      <div class="form-group position-relative">
        <label for="email" class="sr-only">Email</label>
        <input class="form-control input-lg rounded-0" id="email" name="email" type="text" placeholder="Email / Username" required="">
        <i class="fa fa-user fa-lg position-absolute"></i>
        </div>
      <label for="password" class="pull-left sr-only">Password</label>
      <div class="position-relative">
        <input class="form-control input-lg rounded-0" id="password" name="password" type="password" placeholder="Password" required="">
        <i class="fa fa-lock fa-lg position-absolute"></i>
        </div>
      <div class="text-center my-4">
        <button class="btn btn-primary text-white btn-lg text-uppercase" type="submit">Log in</button>
      </div>
    </form>
  </div>
</section>  
</template>
<script>
export default {
    data(){
        return{

        }
    }
}
</script>
<style scoped>
.card-panel {
  box-shadow: rgba(0, 0, 0, 0.1) 0 5px 40px, rgba(0, 0, 0, 0.1) 0 5px 10px;
  border-bottom: 10px solid transparent;
  transition: box-shadow 0.25s;
  padding: 20px;
  margin: 0.5rem 0 1rem;
  border-radius: 2px;
  background-color: #fff;
}

/* Font Awesome Icons */

.form-group a i {
  font-family: FontAwesome;
  margin: 0 auto;
  font-size: 5rem;
  font-style: normal;
}

.min-container .card-panel form .fa {
  top: 13px;
  right: 1rem;
}

/* Media Queries */

@media (min-width: 768px) {
  .min-container {
    max-width: 650px;
  }
}

.min-container {
  margin: 0 auto;
}
</style>