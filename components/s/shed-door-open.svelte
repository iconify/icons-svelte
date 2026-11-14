<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ilvsz3bxn"/><path class="j25afqu4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shed-door-open" {...props}></Icon>
<style>
:global(.ilvsz3bxn) {
  d: path("m3 10l9-7l9 7v11H3Z");
}

:global(.j25afqu4l) {
  d: path("M6 21V11h9v10m0-10l3.25 1.5v7L15 21m-4.5-7.25v4.5m-1.75 0h3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
