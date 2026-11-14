<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t_jy2mbkr"/><path class="ulvifqx-g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:staff-locker" {...props}></Icon>
<style>
:global(.t_jy2mbkr) {
  d: path("M2.5 2.5H12v19H2.5Zm9.5 0h9.5v19H12Zm-7 3h4.5M5 8h4.5m5-2.5H19M14.5 8H19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ulvifqx-g) {
  d: path("M8.25 12.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm9.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm-8.5 1v1.25m9.5-1.25v1.25");
}

</style>
