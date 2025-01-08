<script lang="ts">
	import type { LayoutData } from '../$types';
	let { data }: { data: LayoutData } = $props();
</script>

<h1>Test page</h1>
<p>Data from layout.server.ts: {data.foo}</p>
