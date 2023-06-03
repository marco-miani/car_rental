<script>
    import "../app.css";
    import Header from "$lib/Header.svelte";
</script>

<style>
    @font-face {
        font-family: 'Roboto', sans-serif;
        src: url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700;900&display=swap');
    }

    * {
        font-family: 'Roboto', sans-serif;
    }
</style>

<Header />



  
<footer>
    <h2>
        Isso aqui é pra ser um footer
    </h2>
</footer>

<slot />