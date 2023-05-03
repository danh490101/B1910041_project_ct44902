<script>
    import HeaderShop from '@/components/HeaderShop.vue'
    import toastsVue from '../components/toasts.vue'
    export default {

        components:{
            HeaderShop,
            toastsVue
        },
    }
</script>
<template>
    <HeaderShop></HeaderShop>
    <div class="container">
        <div class="text-center pt-5 pb-5">
            <h1>Đặt hàng thành công !</h1>
            <h2>Cảm ơn bạn đã tin tưởng và mua hàng</h2>
        </div>
        <div class="bg-light px-4 py-3 text-center">
            <div class="row align-items-center text-center">
                    <h6 class="mb-0"><router-link to="/" class="text-body"><i
                          class="fas fa-long-arrow-alt-left me-2 text-center"></i>Quay về trang chủ</router-link></h6>
            </div>
        </div>
    </div>
</template>