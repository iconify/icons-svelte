<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="y7_0n7ckg"/><path class="le_66xblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:wave-energy" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.le_66xblb) {
  d: path("m12.75 5.5l-2 3h2.5l-2 3m-8.5 4.75q1.54-2 3.08 0t3.08 0t3.08 0t3.08 0t3.08 0t3.08 0m-18.48 4q1.54-2 3.08 0t3.08 0t3.08 0t3.08 0t3.08 0t3.08 0");
}

:global(.y7_0n7ckg) {
  width: 7.5px;
  height: 11px;
  x: 8.25px;
  y: 2.75px;
  rx: 2.75px;
}

</style>
