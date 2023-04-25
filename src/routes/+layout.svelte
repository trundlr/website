<script>
    import Header from "./components/Header.svelte";
</script>

<Header />
<slot />

<style>
    :root {
        font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
            "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
        background-color: #404258;
        color: #e8e8ed;
        margin: 0 auto;
    }
</style>
