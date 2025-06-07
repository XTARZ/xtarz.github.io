<template>
    <footer class="main-footer">
        <div class="footer-content">
            <span>&copy; {{ new Date().getFullYear() }} XTARZ. All rights reserved.</span>
        </div>
        <div>
            <a href="https://beian.miit.gov.cn/" target="_blank">赣ICP备2025064389号-1</a>
        </div>
        <div>公安备案号：申请中</div>
    </footer>
</template>

<style scoped>
.main-footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: relative;
    bottom: 0;
    width: 100%;
    font-size: 1rem;
}

.footer-content {
    max-width: 1200px;
    margin: 0 auto;
}
</style>