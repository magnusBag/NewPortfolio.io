<script>
  import Rotater from "./lib/Rotater.svelte";
  import svelteLogo from "./assets/svelte.svg";
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <div class="card h-20 flex flex-col">
    <Rotater right={false} top={"mt-20"} />
    <Rotater right={true} top={"mt-10"} />
  </div>
  <div class="h-[2000px] bg-white" />
</main>
