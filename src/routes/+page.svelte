<script lang="ts">
	import type { LayoutData } from './$types';
	let { data }: { data: LayoutData } = $props();
</script>

<h1>Welcome to SvelteKit</h1>
<p>Data from layout.server.ts: {data.foo}</p>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
