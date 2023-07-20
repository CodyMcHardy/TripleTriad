<script setup>

</script>

<template>
    <div id="container">
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div>
    <div class="cell"></div></div>
</template>

<style scoped>

#container {
    display: grid;
    grid-template-columns: 160px 160px 160px 160px;
}
.cell {
    height: 160px;
    background-image: url('../assets/cell-border.jpg');
    background-size: cover
}
.cell img {
    /* border: solid red 1px; */
    width: 160px;
}

</style>