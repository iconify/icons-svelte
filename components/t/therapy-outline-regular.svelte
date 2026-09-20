<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z0giekeys"/><path class="fm7_cob8y"/><path class="wyl_gxxnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:therapy-outline-regular" {...props}></Icon>
<style>
:global(.fm7_cob8y) {
  d: path("M5 17v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wyl_gxxnb) {
  d: path("M19 17v3");
}

:global(.z0giekeys) {
  d: path("M2 17V8h4v4h12V8h4v9Z");
}

</style>
