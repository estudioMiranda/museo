<template>
	<div>
		<b-button variant="danger">Ejemplo</b-button>
	</div>
</template>

<script>
	export default {
	name: 'NobreComponente'
	} 
</script>

<script>
import NombreComponente from '@/components/NombreComponente.vue'

export default {
	name: 'Home',
	components: {
		NombreComponente
	}
} 
</script>