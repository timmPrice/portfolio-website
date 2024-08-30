<template>
    <div id = "logo">
        <img v-bind:src="logo" alt = "logo" /> 
    </div>
</template>

<script>
    import logo from "../assets/logoRed.jpeg"

    export default {
        name: "LOGO", 
        data: function() {
            return {
                logo: logo
            }

        }    
    }
</script>

<style scoped>
    #logo {
        img {
            width: 25%;
            border-radius: 10%;
        } 
    }
</style>
