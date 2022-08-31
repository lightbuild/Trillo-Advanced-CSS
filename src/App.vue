<script setup lang="ts">

</script>

<template>
  <div class="container">
    <header class="header">
      <img src="./assets/images/logo.png" alt="trillo logo" class="logo">
      <form action="#" class="search">
        <input type="text" class="search__input" placeholder="Search hotels">
        <button class="search__button">
          <svg class="search__icon">
            <use xlink:href="./assets/images/sprite.svg#icon-magnifying-glass"></use>
          </svg>
        </button>
      </form>
      <nav class="user-nav">
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use xlink:href="./assets/images/sprite.svg#icon-bookmark"></use>
          </svg>
          <span class="user-nav__notification">
            7
          </span>
        </div>
        <div class="user-nav__icon-box">
          <svg class="user-nav__icon">
            <use xlink:href="./assets/images/sprite.svg#icon-chat"></use>
          </svg>
          <span class="user-nav__notification">
            13
          </span>
        </div>
        <div class="user-nav__user">
          <img src="./assets/images/user.png" class="user-nav__user-photo" alt="user-photo">
          <span class="user-nav__user-name">Light</span>
        </div>
      </nav>
    </header>
    <div class="content">
      <nav class="sidebar">
        <ul class="side-nav">
          <li class="side-nav__item side-nav__item--active">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="./assets/images/sprite.svg#icon-home"></use>
              </svg>
              <span>Hotel</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="./assets/images/sprite.svg#icon-aircraft-take-off"></use>
              </svg>
              <span>Flight</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="./assets/images/sprite.svg#icon-key"></use>
              </svg>
              <span>Car rental</span>
            </a>
          </li>
          <li class="side-nav__item">
            <a href="#" class="side-nav__link">
              <svg class="side-nav__icon">
                <use xlink:href="./assets/images/sprite.svg#icon-map"></use>
              </svg>
              <span>Tours</span>
            </a>
          </li>
        </ul>
        <div class="legal">
          &copy:2017 by trillo.All right reserved.
        </div>
      </nav>
      <main class="hotel-view">
        Hotel View
      </main>
    </div>
  </div>
</template>

<style scoped lang="scss">

</style>
