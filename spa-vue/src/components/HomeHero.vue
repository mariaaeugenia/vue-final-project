<template>
    <v-container fluid fill-height class="home-hero" style="max-height: 100vh;">
        <v-layout justify-center align-center column pa-5>
            <div class="display-4 font-weight-black white--text text-xs-center">LONDRES</div>
            <div class="display-1 font-weight-bold white--text text-xs-center">O ônibus vermelho de dois andares. O punk solitário em frente ao Picadilly Circus. Os estilosos táxis pretos</div>
        </v-layout>
    </v-container>
</template>

<script>
export default {
    name: 'HomeHero'
};
</script>

<style scoped>
.home-hero {
    background: url('http://source.unsplash.com/Oja2ty_9ZLM');
    background-size: cover;
    width: 100%;
    height: 100%;
}
</style>