<script context="module">
  import Test from './Test.svelte';

  export const meta = {
    title: 'Test',
    component: Test,
  };
</script>

<script lang="ts"> 
  import { Story, Template } from '@storybook/addon-svelte-csf';

  const text = `
I am storybook legacy template.
Hello world.
How are you?

I am good.
`
  console.log(text);
</script>

<Story name="Primary" />

