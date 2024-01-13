<template>
    <div class="main-container">
        <div class="navbar">
            <NavBar/>
        </div>
        <div class="span">
            <span>Home view</span>
        </div>        
    </div>
</template>

<script>
import NavBar from '@/components/NavBar.vue'

export default {
    name: "HomeVue",
    components: {
        NavBar
    }
}
</script>