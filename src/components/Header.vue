<script>
</script>

<template>
    <div class="header">
        <div class="logo"></div>
        <div class="menuBar"></div>
    </div>
</template>

<style>
    .header {
        padding: 32px;
        background-color: #8170af;
        display: flex;
        justify-content: space-between;
    }

    .header .logo {
        width: 50px;
        height: 50px;
        background-color: #c71616;
    }

    .header .menuBar {
        width: 30px;
        height: 5px;
        background-color: #444;
        border-radius: 15px;
        position: relative;
    }

    .header .menuBar::before, .header .menuBar::after {
        content: "";
        width: 30px;
        height: 5px;
        background-color: #444;
        border-radius: 15px;
        position: absolute;
    }
    
    .header .menuBar::before {
        top: 10px;
    }

    .header .menuBar::after {
        top: -10px;
    }
</style>