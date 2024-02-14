<script lang="ts">
  import { queryParam } from "sveltekit-search-params";

  const param = queryParam("param");
</script>

<h1>{$param}</h1>
