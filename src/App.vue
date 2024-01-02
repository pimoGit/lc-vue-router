<script>
import HeaderComp from './components/HeaderComp.vue'
import FooterComp from './components/FooterComp.vue'


export default {
    components: {
        HeaderComp,
        FooterComp
    }
}
</script>

<template>
    <HeaderComp />
    <router-view></router-view>
    <FooterComp />
</template>

<style lang="scss"></style>
