<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m3rd84bde"/><path class="bnumaib7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:security-check-outline-thin" {...props}></Icon>
<style>
:global(.bnumaib7z) {
  d: path("M9 13h6v6H9Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m3rd84bde) {
  d: path("M4 21V8l4 -4h8l4 4v13");
}

</style>
