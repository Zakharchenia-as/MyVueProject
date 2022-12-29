<template>
  <nav class="navbar fixed-top navbar-expand-lg flex-column flex-md-row navbar-dark" style="background-color: #fd7e14">
    <a class="navbar-brand" href = "#">
        <img src = "/images/logo.svg.png" width="70" Height="48">  
        Anime Reactor
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav bd-navbar-nab flex-row">
        <li class="navbar-item">
          <router-link class="nav-link active" to="/">Главная</router-link>
        </li>
        <li class="navbar-item">
          <router-link class="nav-link active" to="/catalog">Каталог аниме</router-link>
        </li>
        <li class="navbar-item">
          <router-link class="nav-link active" to="/about">О нас</router-link>
        </li>
      </ul>
      <ul class="navbar-nav ml-md-auto">
        <li>
            <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Поиск..." aria-label="Search">
            <button class="btn btn-warning my-2 my-sm-0" type="submit">Поиск</button>
            </form>
        </li>
        <li class="navbar-item">
          <router-link class="nav-link active" to="/logon">Войти</router-link>
        </li>
        <li class="navbar-item">
          <router-link class="nav-link active" to="/registration">Зарегистрироваться</router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "MenuTop",
  setup(){
  }
}
</script>

<style scoped>
</style>
