<template>
    <nav>
        <ul>
            <li><a href="">Link</a></li>
            <li><a href="">Link</a></li>
            <li><a href="">Link</a></li>
        </ul>
    </nav>
</template>

<script>
    export default {
        name: 'Navbar',
        data () {
            return {

            }
        }
    }
</script>


<style>
    nav{
        text-align:center;
    }

    nav ul{
        padding:0;
    }

    nav li{
        display: inline-block;
        list-style-type:none;
        margin:0;
    }

    nav ul li a{
        color:aquamarine;
        text-decoration:none;
    }
</style>