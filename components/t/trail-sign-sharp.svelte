<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="n-5nco_2b"/><path class="cp_wmrhmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trail-sign-sharp" {...props}></Icon>
<style>
:global(.cp_wmrhmt) {
  d: path("m6 11.25l3.5-4l2.25 2.5L13.5 8l4.5 3.25m-11.5 3v7m11-7v7");
}

:global(.n-5nco_2b) {
  d: path("M2.75 3.75h18.5v10.5H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
