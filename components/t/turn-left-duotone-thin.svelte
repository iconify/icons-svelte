<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ac92tok8e"/><path class="olxi-hbns"/><path class="a-wplf-uj"/><path class="wd2ghz3oy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:turn-left-duotone-thin" {...props}></Icon>
<style>
:global(.a-wplf-uj) {
  d: path("M16 21V9H7");
}

:global(.ac92tok8e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 21V9H7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.olxi-hbns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 6 7 9l3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wd2ghz3oy) {
  d: path("M10 6 7 9l3 3");
}

</style>
