<script lang="ts">
  let count = 0;
</script>

<p>Counter: {count}</p>

<button
  class="btn btn-secondary"
  on:click={() => {
    count -= 1;
  }}>Remove!</button
>

<button
  class="btn btn-primary"
  on:click={() => {
    count += 1;
  }}>Add!</button
>
