<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cb2yuwq3j"/><path class="lx6korbuc"/><circle class="x05c-_bhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:washing-machine-clock-sharp" {...props}></Icon>
<style>
:global(.cb2yuwq3j) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h16.5v18.5H3.75zm0 4.5h16.5");
}

:global(.lx6korbuc) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 5h.01m3.24 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.x05c-_bhk) {
  cx: 12px;
  cy: 14.25px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
