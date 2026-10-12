<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mzfigxbcc"/><rect class="y1u-8ibcw"/><path class="bdc4p8bad"/><path class="n2fha8b2l"/><path class="c7hk1xptw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:toaster" {...props}></Icon>
<style>
:global(.bdc4p8bad) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 13.5h4");
}

:global(.c7hk1xptw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 20.25v1m11-1v1");
}

:global(.mzfigxbcc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.25v-2a2 2 0 0 1 4 0v2m3 0v-2a2 2 0 0 1 4 0v2");
}

:global(.n2fha8b2l) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 15.25h.01");
}

:global(.y1u-8ibcw) {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 9.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
