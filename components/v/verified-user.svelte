<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="of-h9ev_g"/><path class="xdjir0lzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:verified-user" {...props}></Icon>
<style>
:global(.of-h9ev_g) {
  d: path("M11.372 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.598 0 1.166.058M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7 10.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xdjir0lzh) {
  d: path("M15.75 17.5L17 18.75l2.5-2.5");
}

</style>
