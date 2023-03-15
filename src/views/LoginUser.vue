<script>
    import FormloginVue from "../components/Formlogin.vue";
    import toastsVue from "../components/toasts.vue";
    export default {
        components: {
            FormloginVue,
            toastsVue
        },
    };
</script>
<template>
<toastsVue></toastsVue>
    <h1 class="text-primary" style="margin-top: 100px ; margin-left: 450px;">ĐĂNG NHẬP</h1>
<div class="h-100 border border-dark" style="background-image: url('https://th.bing.com/th/id/OIP.L22frgo19nXuR2GmSED2ggHaE8?w=240&h=180&c=7&r=0&o=5&pid=1.7') ; background-repeat: no-repeat; background-size: cover;">
  <div class="container-fluid h-custom">
    <div class="row d-flex justify-content-center align-items-center h-100">
      <div class="col-md-9 col-lg-6 col-xl-5">
        <img src="https://mdbcdn.b-cdn.net/img/Photos/new-templates/bootstrap-login-form/draw2.webp"
          class="img-fluid" alt="Sample image">
      </div>
      <div class="col-md-8 col-lg-6 col-xl-4 offset-xl-1">
          <FormloginVue></FormloginVue>
      </div>
    </div>
  </div>
</div>  

</template>
