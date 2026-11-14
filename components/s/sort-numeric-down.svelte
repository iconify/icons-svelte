<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oh1-i3bhl"/><path class="m_oal9ugc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sort-numeric-down" {...props}></Icon>
<style>
:global(.m_oal9ugc) {
  d: path("M19 15.75v2.75a2 2 0 0 1-2 2h-1.5");
}

:global(.oh1-i3bhl) {
  d: path("M6.5 4v16m-3-3l3 3l3-3m5.25-11.75l2-1.75v7m-2.25 5.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
