<script lang="ts">
 import Logo from "$lib/Logo.svelte";
 import logoMiamiHerald from "$lib/images/logo-miami-herald.png?enhanced";
</script>

This one fails:

<Logo name="The Miami Herald" src={logoMiamiHerald} />

This one works:

<enhanced:img class="logo" alt="The Miami Herald logo" src={logoMiamiHerald} />

<style>
	.logo {
		width: var(--size);
		height: auto;
	}
</style>
