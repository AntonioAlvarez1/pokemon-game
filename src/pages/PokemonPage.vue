<script lang="ts">
   import PokemonOption from '@/components/PokemonOptions.vue';
   import PokemonPicture from '@/components/PokemonPicture.vue';
   export default{
    components:{PokemonOption,PokemonPicture}
   }

</script>

<template>
    <h1> quien es este Pokemon </h1>
    <PokemonPicture :pokemonId="4" :showPokemon="false"/>
    <PokemonOption/>

</template>

<style>

</style>