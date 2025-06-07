<template>
    <footer class="page-footer">
        <div class="footer-content">
            <span>&copy; {{ new Date().getFullYear() }} XTARZ All rights reserved.</span>
        </div>
        <div><a href="https://beian.miit.gov.cn">赣ICP备2025064389号-1</a></div>
    </footer>
</template>


<style scoped>
.page-footer {
    width: 100%;
    padding: 1rem 0;
    background: #222;
    color: #fff;
    text-align: center;
    position: relative;
    bottom: 0;
    left: 0;
}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
}
</style>
