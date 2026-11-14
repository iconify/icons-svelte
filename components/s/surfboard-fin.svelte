<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gwa_3qbuq"/><path class="pcnjqx5do"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:surfboard-fin" {...props}></Icon>
<style>
:global(.gwa_3qbuq) {
  d: path("M2.5 10c0-1.25 1-1.75 2.5-1.5c6 1 11 .5 16-2c-1.5 4-8 6-16 6c-1.5 0-2.5-1-2.5-2.5Z");
}

:global(.pcnjqx5do) {
  d: path("M5.5 12.5q.75 4.5 4.5 6c-.5-2-.25-4.5.5-6.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
