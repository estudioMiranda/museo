<template>
<div class="container">
    <Navbar></Navbar>
    <img alt="Vue logo" src="../assets/logo.png">
    <Obras></Obras>

</div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Obra from '@/components/Obra.vue'
import Obras from '@/components/Obras.vue'

export default {
    name: 'Inicio',
    components: {
        Navbar,
        Obra,
        Obras
    }
}
</script>
