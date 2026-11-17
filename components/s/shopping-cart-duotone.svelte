<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="atp0ekb8m"/><path class="mn39akbeo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-cart-duotone" {...props}></Icon>
<style>
:global(.atp0ekb8m) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5.75 8H19c.762 0 1.254.984 1 2l-1 4c-.294 1.175-1.118 2-2 2h-7c-.752 0-1.549-.797-2-2Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.mn39akbeo) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4c.752 0 1.549.797 2 2l3 8c.451 1.203 1.248 2 2 2h7c.882 0 1.706-.825 2-2l1-4c.254-1.016-.238-2-1-2H6m2 12a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
