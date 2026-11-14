<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xb68fqbaj"/><path class="kkwhygb5j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:solar-roof-tile" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kkwhygb5j) {
  d: path("M6.75 4.5L11 11h10.5M11 11v9m-.75-15.5L14.5 11m-.75-6.5L18 11");
}

:global(.xb68fqbaj) {
  d: path("M2.5 20v-9l4.25-6.5h10.5L21.5 11v9Z");
}

</style>
