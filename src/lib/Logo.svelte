<script lang="ts">
	export let name: string;
	export let src: any;
</script>

<enhanced:img class="logo" alt={`${name} logo`} {src} />

<style>
	.logo {
		width: var(--size);
		height: auto;
	}
</style>
