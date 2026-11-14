<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nkftt-72u"/><path class="ot94gkbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:updraft" {...props}></Icon>
<style>
:global(.nkftt-72u) {
  d: path("M12 21.5c-1.25-3 1.25-6 0-9V3");
}

:global(.ot94gkbbl) {
  d: path("M6.5 8.5L12 3l5.5 5.5M7 21.5c-1.25-3 1.25-6 0-9m10 9c-1.25-3 1.25-6 0-9");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
