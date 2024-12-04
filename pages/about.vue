<template>
    <div class="container">
        <h1>So sánh Nuxt.js và Vue.js</h1>
        <table class="table">
            <thead>
                <tr>
                    <th>Tiêu chí</th>
                    <th>Nuxt.js</th>
                    <th>Vue.js</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Rendering</td>
                    <td>SSR (Server-Side Rendering)</td>
                    <td>CSR (Client-Side Rendering)</td>
                </tr>
                <tr>
                    <td>Routing</td>
                    <td>Tự động thông qua Pages</td>
                    <td>Cần cấu hình thủ công</td>
                </tr>
                <tr>
                    <td>Quản lý trạng thái</td>
                    <td>Tích hợp dễ dàng với Vuex</td>
                    <td>Cần cấu hình thêm</td>
                </tr>
            </tbody>
        </table>
        <router-link to="/" class="btn btn-primary mt-3">Trở về trang chính</router-link>
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

.table {
    width: 100%;
    margin-bottom: 20px;
    border-collapse: collapse;
}

.table th,
.table td {
    border: 1px solid #dee2e6;
    padding: 8px;
    text-align: left;
}
</style>