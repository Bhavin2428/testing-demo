<template>
  <div class="container mt-5">
    <div class="row justify-content-center">
      <div class="col-md-8">

          <AppButton>Click</AppButton>

            <AppButton>Click Here</AppButton>  
            <!-- Using Slot i have create button -->

        <div class="card">
          <div class="card-header">Demo</div>
               
          <div class="card-body">About Page</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import AppButton from "../components/AppButton";

export default {
   components: {
       AppButton
   }
}
</script>