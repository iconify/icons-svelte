<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sb40gqbga"/><path class="bos0j4biy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:staircase-outline-thin" {...props}></Icon>
<style>
:global(.bos0j4biy) {
  d: path("M3 21h18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sb40gqbga) {
  d: path("M3 21v-4h5v-4h5V9h5V5h3");
}

</style>
