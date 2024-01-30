<script>

export default {
    name: 'AppFooter',


}

</script>

<template>
    <div class="container">
        <div class="row">
            <div class="col">
                <img src="/la-molisana-logo.png" alt="">
            </div>
            <div class="col">
                <ul>
                    <li>
                        <h4>PASTIFICIO</h4>
                    </li>
                    <li>Il pastificio</li>
                    <li>Grano</li>
                    <li>Filiera</li>
                    <li>100 anni di pasta</li>
                    <li>Sartoria della pasta</li>
                </ul>
            </div>
            <div class="col">
                <li>
                    <h4>PRODOTTI</h4>
                </li>
                <li>Le classiche</li>
                <li>Le integrali</li>
                <li>Le speciali</li>
                <li>Le biologiche</li>
                <li>Le gluten-free</li>
            </div>
        </div>
    </div>
</template>

<style>
.container {
    width: 60%;
    margin: auto;
}

.row {
    display: flex;
    justify-content: space-around;
}
</style>