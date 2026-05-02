<script lang="ts">
	import './layout.css';
	import Navbar from '../components/navbar.svelte'

	const { children } = $props();
</script>

<div class="px-100 pt-4 font-serif">
	<div><Navbar /></div>
	{@render children()}
</div>