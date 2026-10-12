<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="tyhetpb4e"/><path class="yqtonkbly"/><circle class="pneh-xn1d"/><rect class="z_461m-kj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:usb" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pneh-xn1d) {
  cx: 7.25px;
  cy: 8.25px;
  r: 1.5px;
}

:global(.tyhetpb4e) {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

:global(.yqtonkbly) {
  d: path("M12 16.5V3.25M9.75 5.5L12 3.25l2.25 2.25m-2.25 9l-4.75-2.75v-2m4.75 2.5l4.75-2.5V8");
}

:global(.z_461m-kj) {
  width: 2.5px;
  height: 2.5px;
  x: 15.5px;
  y: 5.5px;
  rx: 0.5px;
}

</style>
