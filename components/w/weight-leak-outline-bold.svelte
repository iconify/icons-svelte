<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f8t1_w8ci"/><path class="jj-3-pb6g"/><path class="c3a-odz8a"/><path class="wbwra8boi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:weight-leak-outline-bold" {...props}></Icon>
<style>
:global(.c3a-odz8a) {
  d: path("M12 18.5V21");
}

:global(.f8t1_w8ci) {
  d: path("M14 3h3a3 3 0 0 1 3 3v4a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6l3 -3h3");
}

:global(.jj-3-pb6g) {
  d: path("M8 16v2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wbwra8boi) {
  d: path("M16 16v2.5");
}

</style>
