<template>
  <div id="app">
    <nav class="navbar navbar-expand navbar-dark bg-dark">
      <router-link to="/" class="navbar-brand">MyCrud</router-link>
      <div class="navbar-nav mr-auto">
        <li class="nav-item">
          <router-link to="/students" class="nav-link">Show All Students</router-link>
        </li>
        <li class="nav-item">
          <router-link to="/add" class="nav-link">Add New Student</router-link>
        </li>
      </div>
    </nav>
    <div class="container mt-3">
      <router-view />
    </div>
  </div>
</template>
<script>
export default {
  name: "app"
};
</script>
