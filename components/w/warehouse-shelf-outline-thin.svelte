<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e77gki8ci"/><path class="y07a50u1t"/><path class="p0hi_9aen"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:warehouse-shelf-outline-thin" {...props}></Icon>
<style>
:global(.e77gki8ci) {
  d: path("M2 20V10l3 -3h14l3 3v10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p0hi_9aen) {
  d: path("M5 17h14");
}

:global(.y07a50u1t) {
  d: path("M5 13h14");
}

</style>
