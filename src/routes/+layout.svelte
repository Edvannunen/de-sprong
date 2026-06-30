<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>De Sprong</title>
</svelte:head>

<div class="min-h-screen bg-base-200">
	<div class="max-w-3xl mx-auto px-4 py-0">
		{@render children()}
	</div>
</div>
