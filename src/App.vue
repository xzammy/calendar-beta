<template>
  <v-app>
    <v-content>
      <div class="header">
        <h2>致勝先師</h2>
      </div>
      <Calendar />
    </v-content>
  </v-app>
</template>

<script>
import Calendar from "./components/Calendar";

export default {
  name: "App",
  components: {
    Calendar
  },
  data: () => ({
    //
  })
};
</script>

<style>
#app {
  font-family: Roboto, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  background: #102a43;
}
.header {
  padding: 20px 20px;
  color: #f0f4f8;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
