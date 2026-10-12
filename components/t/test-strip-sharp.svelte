<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w3zt_l3hj"/><path class="b05ufrygk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:test-strip-sharp" {...props}></Icon>
<style>
:global(.b05ufrygk) {
  d: path("M5.5 9h5v2.5h-5zm0 6h5v2.5h-5zM16.75 3.25c1.6 2 2.75 3.6 2.75 5.25a2.75 2.75 0 0 1-5.5 0c0-1.65 1.15-3.25 2.75-5.25Z");
}

:global(.w3zt_l3hj) {
  d: path("m6.39 5.3l3.22-1.6l.89-.45v18h-5V5.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
