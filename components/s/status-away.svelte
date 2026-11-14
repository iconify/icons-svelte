<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="flos5eqbe"/><path class="mc3w-3s8h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:status-away" {...props}></Icon>
<style>
:global(.flos5eqbe) {
  d: path("M12.828 21.464a9.5 9.5 0 1 1 8.636-8.636");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mc3w-3s8h) {
  d: path("M17.75 15A3 3 0 1 0 21 18.25A2.5 2.5 0 0 1 17.75 15");
}

</style>
