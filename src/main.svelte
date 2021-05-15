<script>
    import Router from "svelte-spa-router"

    // Components

    // Pages
    import Home from "./routes/home.svelte"

    // Routes
    const routes = {
        "/": Home
    }
</script>

<main>
    <section>
        <Router {routes}/>
    </section>
</main>

<style>
    :global(*) {
        margin: 0;
        padding: 0;
    }
</style>