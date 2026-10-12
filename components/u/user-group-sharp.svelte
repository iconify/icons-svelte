<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="gl0zqx06v"/><circle class="vonm2g1wy"/><path class="jb-5xkbxj"/><circle class="kz9qc0sgp"/><path class="sng0j2bus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:user-group-sharp" {...props}></Icon>
<style>
:global(.gl0zqx06v) {
  cx: 5px;
  cy: 8.75px;
  r: 2px;
}

:global(.jb-5xkbxj) {
  d: path("M3.5 20.25h3.75v-.75c0-2.9-1-5-2.25-5s-2.25 2.1-2.25 5v.75zm14 0h3.75v-.75c0-2.9-1-5-2.25-5s-2.25 2.1-2.25 5v.75z");
}

:global(.kz9qc0sgp) {
  cx: 12px;
  cy: 9.75px;
  r: 2.25px;
}

:global(.sng0j2bus) {
  d: path("M10.5 20.25h3.75v-.75c0-2.9-1-5-2.25-5s-2.25 2.1-2.25 5v.75z");
}

:global(.vonm2g1wy) {
  cx: 19px;
  cy: 8.75px;
  r: 2px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
