<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xiaawqbyt"/><path class="t9y85lbpz"/><path class="ozf7_rb1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rss-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ozf7_rb1s) {
  d: path("M4 4C12.8366 4 20 11.1634 20 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.t9y85lbpz) {
  d: path("M4 12C8.4183 12 12 15.5817 12 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.xiaawqbyt) {
  d: path("M4 20H4.0001");
}

</style>
