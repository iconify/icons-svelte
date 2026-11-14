<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tja79etgw"/><path class="sfylf3b0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:traffic-light-amber" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sfylf3b0e) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 6h.01");
}

:global(.tja79etgw) {
  d: path("M11.875 2h.25A4.375 4.375 0 0 1 16.5 6.375v11.25A4.375 4.375 0 0 1 12.125 22h-.25A4.375 4.375 0 0 1 7.5 17.625V6.375A4.375 4.375 0 0 1 11.875 2M12 6h.01");
}

</style>
