<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m4ez9yb5c"/><path class="n11yjj61m"/><path class="c2uux8yfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:shortcut-tile" {...props}></Icon>
<style>
:global(.c2uux8yfe) {
  d: path("M17 2.5L20 4l-1.5 3");
}

:global(.m4ez9yb5c) {
  d: path("M18 9.9v11.6H2.5V6H10");
}

:global(.n11yjj61m) {
  d: path("M8 16c0-6 4-9.5 12-12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
