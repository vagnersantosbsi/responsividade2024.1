<template>
    <br>
    <ImagensDiversas/>
    <br>
    <VideoUnico/>
    <br>
    <OutroComponente/>
</template>

<script>
import ImagensDiversas from './ImagensDiversas.vue';
import VideoUnico from './VideoUnico.vue';
import OutroComponente from '@/components/OutroComponente.vue';

export default {
    name: 'PaginaPrincipal',
    components: {
        ImagensDiversas, VideoUnico, OutroComponente
    },
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>