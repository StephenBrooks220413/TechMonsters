<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide on choosing layouts to get an idea on<br />
      where we should start, message me for more info:<br />
      <a
        href="mailto:krammer439298@gmail.com"
        class="text-white btn btn-primary"
        >LEARN MORE
      </a>
    </p>
    <br /><br /><br />
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h1>Fluid Designs</h1>
          <br />
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nostrum
          quibusdam, obcaecati earum illo officiis porro tenetur tempora et
          eligendi excepturi voluptas vitae soluta debitis! Ipsum, fugit
          voluptates. Architecto, magni cumque.
        </div>
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1487014679447-9f8336841d58?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1166&q=80"
            alt=""
            width="100%"
            class="img-fluid"
          />
        </div>
      </div>
    </div>
    <br /><br /><br />
    <div class="container">
      <div class="jumbotron text-center">
        <h1>Technologies Used</h1>
      </div>
      <div class="row">
        <div class="col-md-4">
          <h3>Installed CLI Plugins</h3>
          <ul>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
                target="_blank"
                rel="noopener"
                >babel</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-pwa"
                target="_blank"
                rel="noopener"
                >pwa</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-router"
                target="_blank"
                rel="noopener"
                >router</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-vuex"
                target="_blank"
                rel="noopener"
                >vuex</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint"
                target="_blank"
                rel="noopener"
                >eslint</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-typescript"
                target="_blank"
                rel="noopener"
                >typescript</a
              >
            </li>
          </ul>
        </div>
        <div class="col-md-4">
          <h3>Essential Links</h3>
          <ul>
            <li>
              <a href="https://vuejs.org" target="_blank" rel="noopener"
                >Core Docs</a
              >
            </li>
            <li>
              <a href="https://forum.vuejs.org" target="_blank" rel="noopener"
                >Forum</a
              >
            </li>
            <li>
              <a href="https://chat.vuejs.org" target="_blank" rel="noopener"
                >Community Chat</a
              >
            </li>
            <li>
              <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"
                >Twitter</a
              >
            </li>
            <li>
              <a href="https://news.vuejs.org" target="_blank" rel="noopener"
                >News</a
              >
            </li>
          </ul>
        </div>
        <div class="col-md-4">
          <h3>Ecosystem</h3>
          <ul>
            <li>
              <a href="https://router.vuejs.org" target="_blank" rel="noopener"
                >vue-router</a
              >
            </li>
            <li>
              <a href="https://vuex.vuejs.org" target="_blank" rel="noopener"
                >vuex</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/vue-devtools#vue-devtools"
                target="_blank"
                rel="noopener"
                >vue-devtools</a
              >
            </li>
            <li>
              <a
                href="https://vue-loader.vuejs.org"
                target="_blank"
                rel="noopener"
                >vue-loader</a
              >
            </li>
            <li>
              <a
                href="https://github.com/vuejs/awesome-vue"
                target="_blank"
                rel="noopener"
                >awesome-vue</a
              >
            </li>
          </ul>
        </div>
      </div>
    </div>
    <br /><br /><br />
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <img
            src="https://images.unsplash.com/photo-1554306274-f23873d9a26c?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
            alt=""
            width="100%"
            class="img-fluid"
          />
        </div>
        <div class="col-md-6">
          <br /><br />
          <h1>Behind the WebPage</h1>
          <br />
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nostrum
          quibusdam, obcaecati earum illo officiis porro tenetur tempora et
          eligendi excepturi voluptas vitae soluta debitis! Ipsum, fugit
          voluptates. Architecto, magni cumque.
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
