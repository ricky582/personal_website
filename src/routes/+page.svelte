<script lang="ts">
    import Topbar from "../components/Topbar.svelte";


    const page = Topbar;
</script>

<div class="app">
    <svelte:component this={page} />
    <h1>Welcome to SvelteKit</h1>
    <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</div>


<style>
    .app {
        background-color: rgb(44, 36, 74);
        margin: 0;
        height: 100vh;
        width: 100vw;
    }
    * {
        font-family: 'Roboto Mono', 'Trebuchet MS', Arial, sans-serif;
    }
</style>
