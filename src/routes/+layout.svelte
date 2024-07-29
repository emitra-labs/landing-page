<script>
	import { EmitraProvider } from '@emitra-labs/ui';
	import '@emitra-labs/ui/styles.css';
</script>

<svelte:head>
	<title>Emitra Labs</title>
</svelte:head>

<EmitraProvider>
	<slot />
</EmitraProvider>
