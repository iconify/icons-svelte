<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oe5qucsjr"/><path class="es0og7-jz"/><path class="brpj2xbjm"/><path class="bskrurb1h"/><path class="s8vehckhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:run-alert-duotone-regular" {...props}></Icon>
<style>
:global(.brpj2xbjm) {
  d: path("M4 5v14l7 -7Z");
}

:global(.bskrurb1h) {
  d: path("M18 7v5");
}

:global(.es0og7-jz) {
  fill: currentColor;
  d: path("M17 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oe5qucsjr) {
  fill: currentColor;
  d: path("M4 5v14l7 -7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s8vehckhm) {
  d: path("M17 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
