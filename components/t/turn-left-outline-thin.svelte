<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-wplf-uj"/><path class="wd2ghz3oy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-left-outline-thin" {...props}></Icon>
<style>
:global(.a-wplf-uj) {
  d: path("M16 21V9H7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wd2ghz3oy) {
  d: path("M10 6 7 9l3 3");
}

</style>
