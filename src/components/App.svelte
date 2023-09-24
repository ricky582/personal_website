<script lang="ts">
    import Topbar from "../components/Topbar.svelte";
</script>
  
<main class="main">
    <Topbar/>
    <slot></slot>
</main>
  
<style>
    .main {
        background-color: rgb(46, 46, 46);
        margin: 0;
        height: 100vh;
        width: 100vw;
    }
    * {
        font-family: 'Roboto Mono', 'Trebuchet MS', Arial, sans-serif;
    }
</style>