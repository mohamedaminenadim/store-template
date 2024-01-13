<template>
    <div class="main-container" id="nav">
        <ul>
            <li><RouterLink to="/">Home</RouterLink></li>
            <li><RouterLink to="/signup">Signup</RouterLink></li>
        </ul>
    </div>
</template>

<script>
import { RouterLink } from 'vue-router';

export default {
    name: "NavBar",
    data() {
        return {
            navbarPage: true
        };
    },
    methods: {
        changeNavBarPagesState() {
            this.navbarPage = !this.navbarPage;
            console.log("Navbar state changed!!");
        },
    },
    components: { RouterLink }
}
</script>