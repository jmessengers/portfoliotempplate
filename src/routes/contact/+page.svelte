<script>
    import { onMount } from 'svelte';

onMount(() => {
    console.log('attaching particles js');
    const script = document.createElement('script');
    script.src = 'assets/particles.js'; // might be outdated so check for an update can link
    document.body.appendChild(script);


    console.log('attaching app js');
    const config = document.createElement('script');
    config.src = 'assets/app.js'; // might be outdated so check for an update can link
    document.body.appendChild(config);
});
</script>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Text:ital@0;1&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sedan:ital@0;1&display=swap" rel="stylesheet">

<html lang="en">
        <h7>Instagram: X: Facebook: Email: Phone:</h7>
        <div id="particles-js"></div>

</html>

<style>
        #particles-js {
        width: 100%;
        height: 140%;

        position: absolute;
        top: 0;
        z-index: 1;
    }

    h7 {
        position: absolute;
        top: 10%;
        left: 31%;
        font-size: 3.8rem;
        font-family: "DM Serif Text", serif;
        font-weight: 400;
        font-style: normal;
    }

</style>