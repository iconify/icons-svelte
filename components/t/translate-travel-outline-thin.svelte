<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="is6npyb7a"/><path class="g_pok7b1i"/><path class="uqbiloglf"/><path class="cgy8y9byr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:translate-travel-outline-thin" {...props}></Icon>
<style>
:global(.cgy8y9byr) {
  d: path("M17 17v3l3 -3");
}

:global(.g_pok7b1i) {
  d: path("M5 13v3l3 -3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.is6npyb7a) {
  d: path("M2 5h8v8H2Z");
}

:global(.uqbiloglf) {
  d: path("M14 9h8v8h-8Z");
}

</style>
