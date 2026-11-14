<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ttojhb41n"/><path class="b1pgj34_r"/><path class="y90_y5blt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spin-shot" {...props}></Icon>
<style>
:global(.b1pgj34_r) {
  d: path("M18.5 5.5a9 9 0 1 1-13 0");
}

:global(.ttojhb41n) {
  d: path("M7.75 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y90_y5blt) {
  d: path("M3.25 5.5H5.5v2.25M8 10.5q4 2.75 8 0");
}

</style>
