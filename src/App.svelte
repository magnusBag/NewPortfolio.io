<script>
  import svelteLogo from "./assets/svelte.svg";
  import Counter from "./lib/Counter.svelte";
  let y;
</script>

<main>
  <div class="card h-20 flex flex-col">
    <p
      class="absolute  right-1/2 mt-20 z-10"
      style="top: {y * 1.1}px; transform: rotate( {y * 10}deg );"
    >
      {Math.round(y)}
    </p>
    <img
      src={svelteLogo}
      alt="Svelte"
      style="transform: rotate( {y / 10}deg );"
      class=""
    />
    <img src={svelteLogo} alt="Svelte" />
  </div>
</main>
<svelte:window bind:scrollY={y} />
