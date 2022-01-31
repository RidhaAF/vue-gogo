<template>
  <div class="profile">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-md-6">
          <div class="d-flex">
            <div class="flex-shrink-0">
              <img
                src="../assets/profile.jpg"
                alt="Media"
                class="img-fluid rounded-pill user-profile"
              />
            </div>
            <div class="flex-grow-1 ms-3 text-start">
              <h5 class="fw-bold">{{ firstName }} {{ lastName }}</h5>
              <p>{{ bio }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";

export default {
  name: "Profile",
  data: function () {
    return {
      firstName: "Ridha",
      lastName: "Ahmad Firdaus",
      bio: "Lorem ipsum dolor, sit amet consectetur adipisicing elit. Excepturi numquam ut architecto autem culpa quos voluptatibus nobis nostrum laboriosam nemo.",
    };
  },
};
</script>

<style scoped>
.user-profile {
  width: 80px;
}
</style>
