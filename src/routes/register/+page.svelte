<script lang="ts">
  import { AuthForm } from "$components";
  import type { PageProps } from "./$types";

  let { form }: PageProps = $props();
</script>

<AuthForm isRegistration={true} {form} />
