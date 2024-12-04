<template>
    <div class="container">
        <h1>Lợi ích khi sử dụng Nuxt.js</h1>
        <ul class="list-group">
            <li class="list-group-item">Hỗ trợ SSR và CSR cho hiệu suất tối ưu.</li>
            <li class="list-group-item">Quản lý routing tự động thông qua hệ thống Pages.</li>
            <li class="list-group-item">Tích hợp dễ dàng với Vuex cho quản lý trạng thái.</li>
            <li class="list-group-item">Hỗ trợ SEO tốt hơn nhờ SSR.</li>
            <li class="list-group-item">Quản lý cấu hình đơn giản với các modules có sẵn.</li>
        </ul>
        <router-link to="/" class="btn btn-primary mt-3">Trở về trang chính</router-link>
        <router-link to="/about" class="btn btn-secondary mt-3 ml-3">Xem so sánh với Vue.js</router-link>
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
    margin-bottom: 20px;
}

.list-group {
    margin-bottom: 20px;
}
</style>