<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m0n9262pn"/><path class="b7xitabad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:turn-slight-right" {...props}></Icon>
<style>
:global(.b7xitabad) {
  d: path("M15.5 9.5V4H10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m0n9262pn) {
  d: path("M8.5 20.5V11l7-7");
}

</style>
