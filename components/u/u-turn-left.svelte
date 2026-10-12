<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bpt8-n4_z"/><path class="hm6ht6b6s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:u-turn-left" {...props}></Icon>
<style>
:global(.bpt8-n4_z) {
  d: path("M3.75 18.5h11a4.75 4.75 0 0 0 0-9.5H4.25");
}

:global(.hm6ht6b6s) {
  d: path("M7.75 12.5L4.25 9l3.5-3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
