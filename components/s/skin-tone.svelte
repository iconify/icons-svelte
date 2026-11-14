<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t4dormb6m"/><path class="wqfynkb3z"/><path class="q_omj7xaj"/><path class="pz-lk_bvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:skin-tone" {...props}></Icon>
<style>
:global(.pz-lk_bvz) {
  d: path("M15.5 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.q_omj7xaj) {
  d: path("M11 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.t4dormb6m) {
  fill: currentColor;
  d: path("M2 12a3.25 3.25 0 1 0 6.5 0A3.25 3.25 0 1 0 2 12Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wqfynkb3z) {
  fill: currentColor;
  d: path("M6.5 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

</style>
