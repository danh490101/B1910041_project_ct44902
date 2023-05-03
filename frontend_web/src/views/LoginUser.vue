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
    
<div class="h-80">
  <div class="container-fluid h-custom">
    <div class="row d-flex justify-content-center align-items-center h-80 mt-5">
      <div class="col-md-9 col-lg-6 col-xl-5">
        <img src="../assets/img/login.jpg"
          class="img-fluid" alt="Sample image">
      </div>
      <div class="col-md-8 col-lg-6 col-xl-4 offset-xl-1">
        <h1 style="margin-top: 50px ; margin-left: 100px; font-family: Copperplate; font-size:80px;">Đăng Nhập</h1>
        <br>
          <FormloginVue></FormloginVue>
      </div>
    </div>
  </div>
</div>  

</template>
