<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="j8-rqqbmt"/><path class="b0phr5k0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tv-browser" {...props}></Icon>
<style>
:global(.b0phr5k0d) {
  d: path("M39.207 24.21h-6.091l-5.167 12.706l-7.898-25.832l-5.167 12.706h-6.09");
}

:global(.j8-rqqbmt) {
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
