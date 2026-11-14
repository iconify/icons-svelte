<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yv2w9nkie"/><path class="ces43tbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:waist-size" {...props}></Icon>
<style>
:global(.ces43tbbl) {
  d: path("M7.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 7h11.5m0-2v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yv2w9nkie) {
  d: path("M3 11a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

</style>
