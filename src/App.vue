<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <i class="fab text-success top-icon fa-optin-monster"></i>
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-mdb-toggle="collapse"
          data-mdb-target="#navbarText"
          aria-controls="navbarText"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link class="nav-link active" aria-current="page" to="/">
                Home
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/about">
                About
              </router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link active" to="/contact">
                Contact
              </router-link>
            </li>
          </ul>
          <span class="navbar-text">
            <router-link class="nav-link active" to="/services">
              Services
            </router-link>
          </span>
        </div>
      </div>
    </nav>
  </div>
  <router-view />
</template>

<script>
import * as mdb from "mdb-ui-kit"; // lib

export default {
  mdb
};
</script>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.top-icon {
  font-size: 28px !important;
}
#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
