<script>
    import { base } from '$app/paths'
</script>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Text:ital@0;1&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Sedan:ital@0;1&display=swap" rel="stylesheet">

<html lang="en">
    <div class="introduction">
    <h1>Welcome to My Portfolio</h1>
    <p1>I'm [Your Name], a [Your Profession or Field] based in [Your Location]. This portfolio showcases my passion and skills in [Your Field].
        <br>
        Explore my work to see how I bring creativity and expertise to projects. Feel free to reach out for inquiries or collaboration opportunities.
        <br>
        Thank you for visiting!</p1>
</div>

<div class="work">
    <h2>Featured projects</h2>
    <h3>Check out my featured work</h3>
    <p2>Here are some of my projects that I've worked on that showcase my skills and expertise. If showcase doesnt work hit the back arrow and try again.</p2>
</div>

<div class="contactinfo">
    <a href="{base}/contact"><h4>Get in touch</h4></a>
    <p3>Have a project in mind or just want to talk? Contact information below I'll get back to you as soon as possible.</p3>
</div>
<div id="rectanglewrap">
<div class="rectangle"><!-- svelte-ignore a11y-missing-content --><a class="work2" href="{base}/workdisplay"></a></div>
<div class="rectangle"><!-- svelte-ignore a11y-missing-content --><a class="work2" href="{base}/workdisplay"></a></div>
<div class="rectangle"><!-- svelte-ignore a11y-missing-content --><a class="work2" href="{base}/workdisplay"></a></div>
</div>
<div id="particles-js"></div>
<script src="assets/particles.js"></script>
<script src="assets/app.js"></script>
</html>

<style>
    html {
        background-color: darkgrey;
    }
    #particles-js {
        width: 100%;
        height: 140%;

        position: absolute;
        top: 0;
        z-index: 1;
    }
    #rectanglewrap {
        display: flex;
        justify-content: center;
        flex-wrap: wrap;

        gap: 3rem;
        margin-top: -35%;
    }
    .rectangle {
        width: 17.5vw;
        height: 35vh;
        background-color: white; 
        z-index: 2;
        position: relative;
    }

    .rectangle:hover {
        transition: all 0.5s ease-out;
        filter: brightness(60%);
    }
    
    .work2 {
        content: "";
        position: absolute;
        top: 0px;
        right: 0px;
        bottom: 0px;
        left: 0px;
    }
    h1 {
        font-size: 3rem;
        font-family: "DM Serif Text", serif;
        font-weight: 400;
        font-style: normal;
    }
    p1 {
        font-size: 1.5rem;
        font-family: "Sedan", serif;
        font-weight: 400;
        font-style: normal;
    }
    .introduction {
        margin-top: 10%;
        margin-left: 3%;
    }
    h2 {
        font-size: 1.5rem;
        font-family: "Sedan", serif;
        font-weight: 400;
        font-style: normal;
    }
    h3 {
        font-size: 3rem;
        font-family: "DM Serif Text", serif;
        font-weight: 400;
        font-style: normal;
    }
    p2 {
        font-size: 1.5rem;
        font-family: "Sedan", serif;
        font-weight: 400;
        font-style: normal;
    }
    .work {
        margin-top: 15%;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        flex-direction: column;
        align-items: center;
    }
    h4 {
        font-size: 3rem;
        font-family: "DM Serif Text", serif;
        font-weight: 400;
        font-style: normal;
    }
    p3 {
        font-size: 1.5rem;
        font-family: "Sedan", serif;
        font-weight: 400;
        font-style: normal;
    }
    .contactinfo {
        margin-top: 30%;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        flex-direction: column;
        align-items: center; 
    }
</style>