<template>
  <v-app light>
    <v-toolbar fixed>
      <v-toolbar-title v-text="title"></v-toolbar-title>
    </v-toolbar>
    <main>
      <v-container fluid>
        <v-slide-y-transition mode="out-in">
          <v-layout column align-center>
            <img src="/static/img/v.png" alt="Vuetify.js" class="mb-5">
            <blockquote>
              &#8220;First, solve the problem. Then, write the code.&#8221;
              <footer>
                <small>
                  <em>&mdash;John Johnson</em>
                </small>
              </footer>
            </blockquote>
          </v-layout>
        </v-slide-y-transition>
      </v-container>
    </main>
  </v-app>
</template>

<script>
  export default {
    data() {
      return {
        title: 'ODYSSEY',
      };
    },
  };
</script>

<style lang="stylus">
  @import './stylus/main'
</style>
