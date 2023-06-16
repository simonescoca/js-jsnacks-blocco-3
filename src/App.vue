<script>
    // Usando il progetto creato ieri in classe, vue3-header, aggiungere un componente figlio di AppHeader,
    // che si chiami NavLink, istanziare tanti navlink quanti link sono presenti nella navbar e
    // passare il suo nome come prop da AppHeader a NavLink
    import AppHeader from './components/AppHeader.vue'
    export default {
        components: {
            AppHeader
        },
        data() {
            return {

            }
        }
    }
</script>

<template>
    <AppHeader />
</template>

<style lang="scss" scoped>
</style>