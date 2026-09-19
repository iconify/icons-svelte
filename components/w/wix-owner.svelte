<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j_42ulb5v"/><path class="u64aich5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:wix-owner" {...props}></Icon>
<style>
:global(.j_42ulb5v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M25.796 19v10m2.876-10l6.625 10m0-10l-6.625 10");
}

:global(.u64aich5z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.703 19l-2.5 10l-2.5-10l-2.5 10l-2.5-10");
}

</style>
