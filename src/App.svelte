<script>
  import svelteLogo from "./assets/svelte.svg";
  import tailwindLogo from "./assets/tailwind.svg";
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <div class="flex grid-cols-3 gap-8 justify-center mt-5">
    <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
      <img src="/vite.svg" class="h-10" alt="Vite Logo" />
    </a>
    <a href="https://svelte.dev" target="_blank" rel="noreferrer">
      <img src={svelteLogo} class="h-10" alt="Svelte Logo" />
    </a>
    <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
      <img src={tailwindLogo} class="h-9" alt="tailwind Logo" />
    </a>
  </div>
  <h1 class="text-3xl mt-10">Vite + Svelte + Tailwind</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official
    Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">Click on the Vite and Svelte logos to learn more</p>
</main>
