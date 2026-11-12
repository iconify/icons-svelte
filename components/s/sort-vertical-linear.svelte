<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-mwjt3jk"/><path class="jwe4axb7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sort-vertical-linear" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jwe4axb7c) {
  d: path("M8 6L8 18M4 13.875L8 18L12 13.875");
}

:global(.p-mwjt3jk) {
  d: path("M16 18L16 6M12 10.125L16 6L20 10.125");
}

</style>
