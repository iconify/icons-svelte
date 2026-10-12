<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="oj39evbgb"/><circle class="xhuo7yavf"/><path class="k2s5fpbss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:train-station-sharp" {...props}></Icon>
<style>
:global(.k2s5fpbss) {
  d: path("M9 21.25v-3.5a3 3 0 0 1 6 0v3.5M5.25 15v3m13.5-3v3");
}

:global(.oj39evbgb) {
  d: path("M2.75 20.75V12h5V6.5l.37-.33l3.51-3.09l.37-.33l.37.33l3.51 3.09l.37.33V12h5v9.25H2.75z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xhuo7yavf) {
  cx: 12px;
  cy: 8.75px;
  r: 1.75px;
}

</style>
