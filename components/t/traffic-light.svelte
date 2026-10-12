<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="km4uzacsz"/><circle class="w7ips4bys"/><path class="dxneo4t6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:traffic-light" {...props}></Icon>
<style>
:global(.dxneo4t6j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01M12 16.75h.01");
}

:global(.km4uzacsz) {
  width: 10.5px;
  height: 18.5px;
  x: 6.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.5px;
}

:global(.w7ips4bys) {
  cx: 12px;
  cy: 7.25px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
