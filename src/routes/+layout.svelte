<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>
{@render children()}
