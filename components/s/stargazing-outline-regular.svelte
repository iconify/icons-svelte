<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znfuzdoyp"/><path class="mt0duqbnk"/><path class="luzoskb2e"/><path class="l1lmw_bdv"/><path class="saj3disjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stargazing-outline-regular" {...props}></Icon>
<style>
:global(.l1lmw_bdv) {
  d: path("M13 11h6");
}

:global(.luzoskb2e) {
  d: path("M16 8v6");
}

:global(.mt0duqbnk) {
  d: path("M4 6h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.saj3disjq) {
  d: path("M3 20c4 -3 14 -3 18 0");
}

:global(.znfuzdoyp) {
  d: path("M7 3v6");
}

</style>
