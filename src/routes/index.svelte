<script>
  //Optional, console logging only
  import { onMount } from "svelte";

  onMount(() => {
    console.log("Functions are coming...");

    fetch("/.netlify/functions/hello")
      .then(response => response.json())
      .then(json => console.log(json));
  });

  import HomeSlider from "../components/HomeSlider.svelte";
  import Intro from "../components/Intro.svelte";
  import About from "../components/About.svelte";
</script>

<svelte:head>
  <title>Home | Madalin Antonoiu</title>
</svelte:head>

<HomeSlider/>
<Intro/>
<About/>