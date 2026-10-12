<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="z83cimu8h"/><path class="a7xbknbyy"/><path class="i8kng0bqs"/><rect class="rx9jwjbye"/><path class="lcc9ouy6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:soil-sensor" {...props}></Icon>
<style>
:global(.a7xbknbyy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01");
}

:global(.i8kng0bqs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 10v6m3-6v6m4.25-11.5a3 3 0 0 1 0 4.5m2-6a5.5 5.5 0 0 1 0 7.5");
}

:global(.lcc9ouy6n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 16v3m3-3v3");
}

:global(.rx9jwjbye) {
  width: 18.5px;
  height: 5.25px;
  x: 2.75px;
  y: 16px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.z83cimu8h) {
  width: 7px;
  height: 6.5px;
  x: 8.5px;
  y: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

</style>
