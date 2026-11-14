<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irv3q095h"/><path class="cq7dijbml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:water-tank-empty" {...props}></Icon>
<style>
:global(.cq7dijbml) {
  d: path("M7 16.5q2.5-1.5 5 0t5 0");
}

:global(.irv3q095h) {
  d: path("M4 3.5v15a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2v-15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
