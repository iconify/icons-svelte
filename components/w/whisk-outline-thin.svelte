<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z_j864liq"/><path class="hx7cfzbbm"/><path class="l6rp-_-ny"/><path class="mww7ccc2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:whisk-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hx7cfzbbm) {
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
}

:global(.l6rp-_-ny) {
  d: path("M10 21c0 -6 1 -12 2 -12");
}

:global(.mww7ccc2b) {
  d: path("M14 21c0 -6 -1 -12 -2 -12");
}

:global(.z_j864liq) {
  d: path("M12 2v7");
}

</style>
