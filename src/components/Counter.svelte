<script lang="ts">
  let count = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button
  class="rounded-md border border-transparent bg-gray-800 px-4 py-2
font-medium text-white hover:border-gray-500 focus:border-gray-500 focus:outline-none
focus:ring-2 focus:ring-gray-500 focus:ring-offset-2"
  on:click="{increment}"
>
  count is {count}
</button>
