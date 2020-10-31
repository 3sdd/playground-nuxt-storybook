<template>
    <div class="bg-black w-10">
        <nuxt-link to="https://nuxtjs.org">
            {{text}}
        </nuxt-link>
    </div>
</template>

<script>
export default {
    props:{
        text:{
            type:String,
            default:"Nuxt.js",
        }
    },
}
</script>