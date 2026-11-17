<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fkj2w-bbh"/><path class="xnpud1bub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-text-duotone-round" {...props}></Icon>
<style>
:global(.fkj2w-bbh) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m16 10l4-4c.369-.369 1-.369 1 0v12c0 .369-.631.369-1 0l-4-4h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.xnpud1bub) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 10l4-4c.369-.369 1-.369 1 0v12c0 .369-.631.369-1 0l-4-4h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1zM3 9h6M6 9v6");
}

</style>
