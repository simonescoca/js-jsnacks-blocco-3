<script>
    import NavLink from './NavLink.vue'
    export default {
        components: {
            NavLink
        },
        data() {
            return {
                navLinks: ["CHARACTERS", "COMICS", "MOVIES", "TV", "GAMES", "COLLECTIBLES", "VIDEOS", "FANS", "NEWS", "SHOP"]
            }
        }
    }
</script>

<template>
    <NavLink :link="nonsaprei"/>
</template>

<style lang="scss" scoped>
</style>