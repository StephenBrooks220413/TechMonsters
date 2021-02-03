<template>
  <div class="home">
    <div class="bg-image">
      <img
        src="https://images.unsplash.com/photo-1485827404703-89b55fcc595e?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
        class="img-fluid img-max"
        alt="Sample"
        width="100%"
      />
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <h1 class="text-white display-4">
            TechMonsters<br />
            580-309-0236
          </h1>
        </div>
      </div>
    </div>
    <br /><br /><br /><br />
    <div class="jumbotron text-center">
      <h1 class="display-4">Services Offered</h1>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <img
              src="https://images.unsplash.com/photo-1602265585142-6b221b9b2c24?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=925&q=80"
              alt=""
              class="img-fluid"
              width="82%"
            />
            <h4>Web Design</h4>
          </div>
          <div class="col-md-4">
            <img
              src="https://media.gettyimages.com/vectors/website-under-construction-vector-id165737185?k=6&m=165737185&s=612x612&w=0&h=697W3pB7QK0JXSmYfmkjCrgO07B_F_gUAvl2465T5JQ="
              alt=""
              class="img-fluid"
              width="100%"
            />
            <h4>Maintenance</h4>
          </div>
          <div class="col-md-4">
            <img
              src="https://media.gettyimages.com/photos/progress-in-action-picture-id185247411?k=6&m=185247411&s=612x612&w=0&h=P4KbPQdHLz15WLPVmqM0xGMTm5hw1PjZftbNHlgSEOI="
              alt=""
              class="img-fluid"
              width="90%"
            />
            <h4>Upgrading</h4>
          </div>
        </div>
      </div>
    </div>
    <br /><br /><br /><br />
    <!-- Carousel wrapper -->
    <HelloWorld msg="Your Vue.js + TypeScript Developer" />
    <br /><br /><br /><br />
    <div class="container">
      <h1 class="text-center">Contact By Team</h1>
      <br /><br />
      <div class="row">
        <div class="col-md-4">
          <br /><br />
          <div class="card content-1">
            <div class="card-body text-white">
              <h4 class="card-title">VP of Sales</h4>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <button type="button" class="btn btn-primary">Inquire</button>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <br /><br />
          <div class="card content-2">
            <div class="card-body text-white">
              <h5 class="card-title">Web Developer</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <button type="button" class="btn btn-primary">Inquire</button>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <br /><br />
          <div class="card content-3">
            <div class="card-body text-white">
              <h5 class="card-title">Consulting</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
              <button type="button" class="btn btn-primary">Inquire</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <br />
    <br />
    <div class="container">
      <div class="row">
        <div class="col-md-12 text-primary">
          <i class="fab icon fa-twitter"></i>
          <i class="fab icon fa-facebook"></i>
          <i class="fab icon fa-linkedin"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style scoped>
.img-max {
  max-height: 850px !important;
}
.content-1 {
  background: url(https://free4kwallpapers.com/uploads/originals/2015/07/14/matrix-code.jpg)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  max-height: 380px !important;
  width: 100%;
}
.content-2 {
  background: url(https://free4kwallpapers.com/uploads/originals/2015/07/14/matrix-code.jpg)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  max-height: 380px !important;
  width: 100%;
}
.content-3 {
  background: url(https://free4kwallpapers.com/uploads/originals/2015/07/14/matrix-code.jpg)
    no-repeat center center fixed;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  max-height: 380px !important;
  width: 100%;
}
.icon {
  font-size: 35px !important;
  letter-spacing: 34px !important;
}
</style>
