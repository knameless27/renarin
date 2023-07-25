<template>
    <div class="menu">
        <ul>
            <li><a>Home</a></li>
        </ul>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.menu {
    position: fixed;
    top: 0;
    width: 100%;
    overflow: hidden;
    background-color: #333;
}

ul {
    list-style-type: none;
}

li {
    float: left;
}

li a {
    display: block;
    color: rgb(233, 229, 229);
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover {
    cursor: pointer;
    background-color: #111;
    border-radius: 6px 6px 0 0;
}
</style>
