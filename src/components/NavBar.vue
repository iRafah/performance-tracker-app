<template>
    <div class="top-menu">
        <div class="branding">
            <img alt="Vue logo" src="../assets/tracker_icon.png" class="logo"/>
            <span class="brand_name">Performance Tracker</span>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
    .top-menu {
        width: 100%;
        padding: .2rem 0;
        background: #007691;
        text-align: left;
        height: 4rem;
    }

    .top-menu .branding {
        display: flex;
        font-family: 'Open Sans';
        color: #fff;
        font-weight: bold;
        margin: .6rem 0;
    }

    .top-menu .logo {
        width: 3rem;
        margin: 0 15px;
    }

    .top-menu .brand_name {
        margin-top: .7rem;
        font-size: 1rem;
    }
</style>