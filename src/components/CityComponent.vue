<script>
export default {
    name:"CityComponent",
    props: ["img"],
}
</script>

<template>
    <div class="city">
        <img :src="img" />
    </div>
</template>

<style scoped>
    .city { 
    padding: 2px; 
    white-space: nowrap; 
    width: 350px; 
    height: 350px; 
    border-style: solid; 
    border-radius: 5px; 
    border-color: grey; 
    } 
    
    h1 { 
    overflow: hidden; 
    text-overflow: ellipsis; 
    }
</style>