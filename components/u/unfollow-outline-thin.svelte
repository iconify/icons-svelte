<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ejfmpibyt"/><path class="fgh6wnb3a"/><path class="p8a31xr4o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unfollow-outline-thin" {...props}></Icon>
<style>
:global(.ejfmpibyt) {
  d: path("M7 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.fgh6wnb3a) {
  d: path("M6 17a4 4 0 0 1 8 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p8a31xr4o) {
  d: path("M16 12h6");
}

</style>
