<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ricsl-blc"/><path class="kjki_4mtw"/><path class="apfnny4vx"/><path class="wneoubc6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spring-outline-thin" {...props}></Icon>
<style>
:global(.apfnny4vx) {
  d: path("M12 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kjki_4mtw) {
  d: path("M4 13c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

:global(.ricsl-blc) {
  d: path("M12 12v9");
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

</style>
