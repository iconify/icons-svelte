<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dmjxi0bep"/><circle class="w7ips4bys"/><path class="dxneo4t6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:traffic-light-sharp" {...props}></Icon>
<style>
:global(.dmjxi0bep) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 2.75h10.5v18.5H6.75z");
}

:global(.dxneo4t6j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01M12 16.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.w7ips4bys) {
  cx: 12px;
  cy: 7.25px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
