<script>
import comics from '../comics.js';
import AppComicsSon from './AppComicsSon.vue';

export default {

    name: 'AppComics',

    components: { AppComicsSon },

    data() {
        return {
            comics,
        }
    }
}
</script>

<template>
    <div class="col-2 pt-2" v-for="comic in comics">

        <AppComicsSon :lnThumb="comic.thumb" :lnPrice="comic.price" :lnSeries="comic.series" :lnType="comic.type" />

    </div>
</template>

<style lang="scss" scoped></style>