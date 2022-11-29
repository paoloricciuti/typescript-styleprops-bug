<script lang="ts">
  export let text: string;

  type $$Props = {
    text: string;
    "--bg": string;
  };
</script>

<p>{text}</p>

<style>
  p {
    background-color: var(--bg);
  }
</style>
