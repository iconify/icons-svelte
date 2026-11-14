<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ie9fhtb8y"/><path class="dqh8ebbgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wave-reflection" {...props}></Icon>
<style>
:global(.dqh8ebbgp) {
  d: path("M16.5 5H20v3.5M3 20h18");
}

:global(.ie9fhtb8y) {
  d: path("m4 5l8 11.5L20 5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
