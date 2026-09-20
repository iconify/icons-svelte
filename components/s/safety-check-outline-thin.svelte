<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="ylnxs8amf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:safety-check-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.ws1d0fbts) {
  d: path("M20 4v16");
}

:global(.ylnxs8amf) {
  d: path("m8 12 2 2 6 -6");
}

</style>
