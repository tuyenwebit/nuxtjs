<template>
    <div class="container">
        <h1>Giới thiệu về Nuxt.js</h1>
        <p>
            Nuxt.js là một framework mạnh mẽ cho Vue.js, giúp phát triển ứng dụng
            SSR (Server-Side Rendering) và SPA (Single Page Application) một cách dễ dàng.
        </p>
        <p>
            Hãy tìm hiểu thêm về:
            <router-link to="/about" class="btn btn-info mx-2">So sánh Nuxt.js và Vue.js</router-link>
            <router-link to="/benefits" class="btn btn-success mx-2">Lợi ích của Nuxt.js</router-link>
        </p>
    </div>
</template>

<style scoped>
.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

h1 {
    color: #35495e;
}
</style>