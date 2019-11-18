<template>
    <header class="header">
        <h1 class="header__title">Welcome to this</h1>
        <p class="header__intro">This is an intro of sorts just for the hell of it.</p>
        <div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
        </div>
    </header>
</template>

<script>
export default {
  name: "Header",
}
</script>

<style lang="scss" scoped>
    .header__title {
        font-size: 4rem;
    }

    .header__intro {
        font-size: 1.6rem;
    }
</style>