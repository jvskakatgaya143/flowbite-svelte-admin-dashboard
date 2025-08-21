<script lang="ts">
  import { LiquidGlass } from 'liquid-glass-svelte';
  import type { LiquidGlassPanelProps } from './types';

  let { options = {}, children, ...rest }: LiquidGlassPanelProps = $props();
</script>

<LiquidGlass {options} {...rest}>
  {@render children()}
</LiquidGlass>

<!--
@component
## Props
@prop options = {}
-->
