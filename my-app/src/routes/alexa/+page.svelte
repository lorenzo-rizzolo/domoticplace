<svelte:head>
    <title>{name}</title>
</svelte:head>

<h1>{name}</h1>

<div class="prodotto">
    Amazon ALexa
    <img src="alexa.png" alt="alexa">
</div>
<div class="prodotto">
    Allarmi Alexa
    <img src="allarmi.png" alt="alexa">
</div>

<script>
    let name = "Alexa";
</script>