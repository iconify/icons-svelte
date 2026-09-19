<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwg0gl7pg"/><circle class="neag2rbvc"/><path class="sm0ad09zv"/><circle class="stjv0pdcv"/><circle class="uqlamj4tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-summarize" {...props}></Icon>
<style>
:global(.neag2rbvc) {
  cx: 8px;
  cy: 8px;
  r: 1px;
  fill: currentColor;
}

:global(.rwg0gl7pg) {
  fill: currentColor;
  d: path("M14 5H5v14h14v-9h-5zM8 17c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m0-4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m0-4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.sm0ad09zv) {
  fill: currentColor;
  d: path("M15 3H5c-1.1 0-1.99.9-1.99 2L3 19c0 1.1.89 2 1.99 2H19c1.1 0 2-.9 2-2V9zm4 16H5V5h9v5h5z");
}

:global(.stjv0pdcv) {
  cx: 8px;
  cy: 12px;
  r: 1px;
  fill: currentColor;
}

:global(.uqlamj4tr) {
  cx: 8px;
  cy: 16px;
  r: 1px;
  fill: currentColor;
}

</style>
