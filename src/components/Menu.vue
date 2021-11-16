<template>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
<div class="container">
<router-link class="navbar-brand" to="/">DEMOAPP</router-link>
<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
<span class="navbar-toggler-icon"></span>
</button>
<div class="collapse navbar-collapse" id="navbarSupportedContent">
<ul class="navbar-nav me-auto mb-2 mb-lg-0">
<li class="nav-item">
<router-link class="nav-link" to="/">HOME</router-link>
</li>
<li class="nav-item">
<router-link class="nav-link" to="/about">ABOUT</router-link>
</li>
</ul>
<form class="d-flex">
<input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
<button class="btn btn-outline-success" type="submit">Search</button>
</form>
</div>
</div>
</nav>

</template>

<script>
export default {
name: 'Menu'
}
</script>

<style lang="css" scoped>

</style>