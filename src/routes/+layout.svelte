<svelte:head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Aboreto">
</svelte:head>

<style>
    body {
        background-color: azure;
    }

    h1, p {
        font-family: 'Aboreto', serif;
    }

    .container {
        height: 100vh;
        margin: auto;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-rows: repeat(3, 1fr);
    }
</style>


<div class="container">
    <slot>
    </slot>
</div>
