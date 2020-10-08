<template>
<div class="inicio">
    <Navbar></Navbar>
    <img alt="Vue logo" src="../assets/logo.png">
    <div>
        <b-button>Button</b-button>
        <b-button variant="danger">Button</b-button>
        <b-button variant="success">Button</b-button>
        <b-button variant="outline-primary">Button</b-button>
    </div>
</div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
    name: 'Inicio',
    components: {
        Navbar
    }
}
</script>
