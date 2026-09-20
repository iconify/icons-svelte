<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n11stdb8v"/><path class="une6cneix"/><path class="z27853bvv"/><path class="covr1fb7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:screwdriver-duotone-bold" {...props}></Icon>
<style>
:global(.covr1fb7y) {
  d: path("m16.5 7.5 3 -3");
}

:global(.n11stdb8v) {
  fill: currentColor;
  d: path("m4 17 4 -4 3 3 -4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.une6cneix) {
  d: path("m4 17 4 -4 3 3 -4 4Z");
}

:global(.z27853bvv) {
  d: path("M9.5 14.5 18 6");
}

</style>
