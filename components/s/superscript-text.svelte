<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y665-3bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:superscript-text" {...props}></Icon>
<style>
:global(.y665-3bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 8.75l9 11m0-11l-9 11M16 5.5a1.75 1.75 0 1 1 3.25.9L16 10.5h3.75");
}

</style>
