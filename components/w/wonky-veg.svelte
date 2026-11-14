<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oxawbwb8k"/><path class="rwdjljwek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wonky-veg" {...props}></Icon>
<style>
:global(.oxawbwb8k) {
  d: path("M4.5 9.5c0-3.5 4-5 6-3l6 7c1 1.5 1 4 4 6.5c-4 0-6-2.5-7-3.5l-8-5c-.5-.5-1-1-1-2Z");
}

:global(.rwdjljwek) {
  d: path("m6 2.5l.25 3.75l-3.5-1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
