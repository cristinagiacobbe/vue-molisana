<script>
import AppLogo from './Logo.vue'

export default {
    name: 'AppHeader',

    components: {
        AppLogo
    }

}

</script>

<template>
    <header>
        <AppLogo></AppLogo>
        <nav>
            <ul class="header_menu">
                <li><a href="#">Home</a></li>
                <li><a href="#">Prodotti</a></li>
                <li><a href="#">Chi siamo</a></li>
                <li><a href="#">Contatti</a></li>
            </ul>
        </nav>
    </header>
</template>

<style>
header {
    text-align: center;
}

.header_menu {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

a {
    text-decoration: none;
    color: black;
}

li {
    list-style: none;
}
</style>
