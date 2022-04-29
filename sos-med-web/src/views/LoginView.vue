<template>
  <div class="container loginMargin">
    <div class="row">
      <div class="col-7"></div>
      <div class="col-5">
        <form class="bg-white p-3 w-custom rounded">
          <div class="mb-3">
            <!-- <label for="exampleInputEmail1" class="form-label">Email address</label> -->
            <input type="email" class="form-control form-control-lg" placeholder="email or username" />
          </div>
          <div class="mb-3">
            <!-- <label for="exampleInputPassword1" class="form-label">Password</label> -->
            <input type="password" class="form-control form-control-lg" placeholder="password" />
          </div>
          <button type="submit" class="btn btn-primary form-control-lg">Login</button>
          <div class="mt-3 border-bottom mb-4">
              <router-link style="text-decoration:none" to="/forgetpassword">Forget your password?</router-link>
          </div>
          <div>
              <button type="button" class="btn btn-primary">Register here</button>
          </div>
        </form>
      </div>
      <!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        ...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>

    </div>
    
  </div>
</template>

<script>
export default {
  name: "LoginView",
  components: {},
};
</script>

<style scoped>
.loginMargin{
    margin-top: 6rem;
}
.w-custom{
    width: 80%;
}
</style>
