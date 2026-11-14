<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r8q9ys35q"/><path class="bg5ytyjxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:street-light-repair" {...props}></Icon>
<style>
:global(.bg5ytyjxp) {
  d: path("M18.75 12v1.5a1 1 0 0 0 1 1h1.5m-8.75 6.25l4.25-4.25");
}

:global(.r8q9ys35q) {
  d: path("M6.5 21.5V7a4 4 0 0 1 4-4h2m0 0h8L19 6.5h-5ZM4 21.5h5m12.25-7a2.5 2.5 0 1 1-2.5-2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
