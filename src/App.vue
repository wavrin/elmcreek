<template>
  <v-app light>
    <v-toolbar class="white">
      <v-toolbar-title v-text="title"></v-toolbar-title>
    </v-toolbar>
    <v-content>
      <section>
        <v-parallax src="../assets/hero.jpeg" height="600">
          <v-layout column align-center justify-center class="white--text">
            <img src="@/assets/logo.png" alt="Elm Creek" height="200" />
            <h1 class="white--text mb-2 display-1 text-xs-center">Elm Creek Technologies</h1>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-layout column wrap class="my-5" align-center>
          <v-flex xs12 sm4 class="my-3">
            <div class="text-xs-center">
              <h2 class="headline">Your technology keeps you up at night</h2>
              <span class="subheading">You've come to the right place</span>
            </div>
          </v-flex>
          <v-flex xs12>
            <v-container grid-list-xl>
              <v-layout row wrap align-center>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">keyboard</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Custom Development</div>
                    </v-card-title>
                    <v-card-text>We are full-stack developers. We build custom software using trusted tools such as Ruby on Rails, Node, AWS, and Vue.js. We value transparency and efficiency.</v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">cloud</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline">Cloud</div>
                    </v-card-title>
                    <v-card-text>We help companies leverage the flexibility, scalability, and cost savings of the cloud. From large migrations to simply moving services to the cloud one-by-one - we will put your mind at ease.</v-card-text>
                  </v-card>
                </v-flex>
                <v-flex xs12 md4>
                  <v-card class="elevation-0 transparent">
                    <v-card-text class="text-xs-center">
                      <v-icon x-large class="blue--text text--lighten-2">business</v-icon>
                    </v-card-text>
                    <v-card-title primary-title class="layout justify-center">
                      <div class="headline text-xs-center">Strategy</div>
                    </v-card-title>
                    <v-card-text>We advise companies on utilizing offshore development for both scalability and cost savings. We also provide web and mobile consulting so that you can make sure you are on the right path.</v-card-text>
                  </v-card>
                </v-flex>
              </v-layout>
            </v-container>
          </v-flex>
        </v-layout>
      </section>

      <section>
        <v-parallax src="../assets/section.jpg" height="380">
          <v-layout column align-center justify-center>
            <div
              class="headline white--text mb-3 text-xs-center"
            >Web development is easy when you work with us</div>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-container grid-list-xl>
          <v-layout row wrap justify-center class="my-5">
            <v-flex xs12 sm4>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Company info</div>
                </v-card-title>
                <v-card-text>Elm Creek Technologies is a software consultancy based in Minneapolis. We work with companies large and small, from startups to established companies, all over the United States.</v-card-text>
              </v-card>
            </v-flex>
            <v-flex xs12 sm4 offset-sm1>
              <v-card class="elevation-0 transparent">
                <v-card-title primary-title class="layout justify-center">
                  <div class="headline">Contact us</div>
                </v-card-title>
                <v-card-text>Reach out to us so we can help.</v-card-text>
                <v-list class="transparent">
                  <!--
                      <v-list-tile>
                        <v-list-tile-action>
                          <v-icon class="blue--text text--lighten-2"
                            >phone</v-icon
                          >
                        </v-list-tile-action>
                        <v-list-tile-content>
                          <v-list-tile-title>phone humber</v-list-tile-title>
                        </v-list-tile-content>
                      </v-list-tile>
                  -->
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">place</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>Minneapolis, US</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                  <v-list-tile>
                    <v-list-tile-action>
                      <v-icon class="blue--text text--lighten-2">email</v-icon>
                    </v-list-tile-action>
                    <v-list-tile-content>
                      <v-list-tile-title>info@elmcreek.io</v-list-tile-title>
                    </v-list-tile-content>
                  </v-list-tile>
                </v-list>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </section>

      <v-footer class="grey">
        <v-layout row wrap align-center>
          <v-flex xs12>
            <div class="white--text ml-3">&#169; 2021 Elm Creek Technologies</div>
          </v-flex>
        </v-layout>
      </v-footer>
    </v-content>
  </v-app>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      title: ""
    };
  }
};
</script>
