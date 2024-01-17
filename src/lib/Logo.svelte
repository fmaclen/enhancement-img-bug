<script lang="ts">
	export let name: string;
	export let src: any;
</script>

<enhanced:img class="logo" alt={`${name} logo`} {src} />

<style lang="scss">
	.logo {
		// https://kit.svelte.dev/docs/images#sveltejs-enhanced-img-intrinsic-dimensions
		width: var(--size);
		height: auto;
	}
</style>
