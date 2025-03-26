<script lang="ts">
	import '../app.css';
	import { prerender } from './+layout';
	
	let { children } = $props();
</script>

{@render children()}
