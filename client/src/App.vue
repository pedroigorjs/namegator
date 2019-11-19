<template>
  <div id="app">
    <div class="slogan text-center">
      <h1>NameGator</h1>
      <br />
      <h6 class="text-secondary">Gerador de nomes utilizando Vue.js, GraphQL e Node</h6>
    </div>
    <div class="main">
      <DomainsList></DomainsList>
    </div>
  </div>
</template>

<script>
import "bootstrap/dist/css/bootstrap.css";
import "font-awesome/css/font-awesome.css";
import DomainsList from "./components/DomainsList";

export default {
	name: "app",
	components: {
		DomainsList
	}
};
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.slogan {
  margin: 30px 0;
}

.main {
  padding: 30px 0;
  background-color: #f1f1f1;
}
</style>
