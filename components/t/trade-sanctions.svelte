<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l8si3eskw"/><path class="h-sqqjb7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:trade-sanctions" {...props}></Icon>
<style>
:global(.h-sqqjb7e) {
  d: path("M9.5 4.5v1.1m3.9 3.9h1.1v-5m-11-1l17 17");
}

:global(.l8si3eskw) {
  d: path("M8.4 4.5H20v11.6m-4.4 3.4H4V7.9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
