<template>
  <div id="app">
    <ul class="nav">
      <li class="nav-item">
        <router-link class="nav-link" to="/">Messages</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/signup">Sign Up</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/login">Log in</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/logout">Log out</router-link>
      </li>
    </ul>

    <router-view/>
  </div>
</template>

<style>
</style>
