<script lang="ts">
	import '../layout.css';
	import Navbar from '../../components/navbar.svelte'

	const { children } = $props();
</script>


{@render children()}