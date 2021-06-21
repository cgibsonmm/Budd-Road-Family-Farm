<script>
	import Navbar from '../components/shared/navbar/index.svelte';
	import '../app.postcss';
</script>

<div class="bg-gray-100 h-screen">
	<Navbar />
	<slot />
</div>
