<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<!-- Favicon moderne - un seul fichier suffit -->
	<link rel="icon" href="/favicon.png" type="image/png" />
	
	<!-- Apple Touch Icon (optionnel pour iOS) -->
	<link rel="apple-touch-icon" href="/favicon.png" />
	
	<!-- Web App Manifest (optionnel pour PWA) -->
	<link rel="manifest" href="/site.webmanifest" />
	
	<!-- Theme Color -->
	<meta name="theme-color" content="#ffffff" />
</svelte:head>

{@render children?.()}