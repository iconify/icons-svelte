<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xiaawqbyt"/><path class="rbfo13byn"/><path class="t8pe7mbkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rss-linear" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rbfo13byn) {
  d: path("M4 12C8.4183 12 12 15.5817 12 20");
}

:global(.t8pe7mbkr) {
  d: path("M4 4C12.8366 4 20 11.1634 20 20");
}

:global(.xiaawqbyt) {
  d: path("M4 20H4.0001");
}

</style>
