<template>
  <div>
    <nav class="navbar navbar-expand-lg bg-white border-bottom navbar-light">
      <router-link class="navbar-brand mr-auto" :to="{name: 'home'}">LaravelBnb</router-link>

      <ul class="navbar-nav">
        <li class="nav-item">
          
        </li>

        
      </ul>
    </nav>

    <div class="container mt-4 mb-4 pr-4 pl-4">
      <router-view></router-view>
    </div>
  </div>
</template>

