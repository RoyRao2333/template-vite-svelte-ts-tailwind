<script lang="ts">
  import logo from '../assets/svelte.svg';
  import Counter from '../components/Counter.svelte';
</script>

<main class="mx-0 p-4 text-center">
  <img
    width="100"
    height="100"
    src="{logo}"
    alt="Svelte Logo"
    class="inline-block"
  />
  <h1
    class="mx-auto my-8 max-w-xs text-6xl font-thin uppercase leading-tight sm:max-w-xs"
  >
    Hello Vite!
  </h1>

  <Counter id="0" />

  <p class="mx-auto my-4 max-w-xs leading-5 sm:max-w-none">
    Visit
    <a class="text-red-600 hover:underline" href="https://svelte.dev">
      svelte.dev
    </a>
    to learn how to build Svelte apps.
  </p>

  <p class="mx-auto my-4 max-w-xs leading-5 sm:max-w-none">
    Check out <a href="https://github.com/sveltejs/kit#readme">SvelteKit</a> for
    the officially supported framework, also powered by Vite!
  </p>

  <div class="p-2 text-red-500">
    <a href="https://svelte.dev/" target="_blank" class="p-2 hover:underline">
      Svelte
    </a>
    +
    <a
      href="https://tailwindcss.com/"
      target="_blank"
      class="p-2 hover:underline"
    >
      Tailwind CSS
    </a>
    +
    <a
      href="https://www.typescriptlang.org/"
      target="_blank"
      class="p-2 hover:underline"
    >
      TypeScript
    </a>
    +
    <a href="https://vitejs.dev/" target="_blank" class="p-2 hover:underline">
      Vite
    </a>
  </div>
</main>

<style lang="postcss">
  :root {
    --svelte-rgb: 255, 62, 0;
  }

  h1 {
    color: rgb(var(--svelte-rgb));
  }
</style>
