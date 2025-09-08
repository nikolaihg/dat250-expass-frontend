<script lang="ts">
  import CreatePollComponent from "./lib/CreatePollComponent.svelte";
  import CreateUserComponent from "./lib/CreateUserComponent.svelte";
  import VoteComponent from "./lib/VoteComponent.svelte";
</script>

<main>
  <h1>Poll application:</h1>

  <div class="card">
    <CreatePollComponent />
    <VoteComponent />
  </div>
  <div>
    <CreateUserComponent />
  </div>
</main>
