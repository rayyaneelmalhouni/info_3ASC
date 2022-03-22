<script>
   import Project from "./Project.svelte";
   const projects_data = [1, 2, 3, 4]
</script>

{#each projects_data as project}
    <Project />
{/each}