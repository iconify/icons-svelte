<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="k0-3zzb2q"/><path clip-rule="evenodd" class="hz_ux95at"/><path class="fk7obbb6p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tab-sharp-duotone" {...props}></Icon>
<style>
:global(.fk7obbb6p) {
  d: path("M12 3V8H21M3 3H21V21H3V3Z");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.hz_ux95at) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 3H12V8H21V3Z");
  stroke: none;
}

:global(.k0-3zzb2q) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 2H21C21.552 2 22 2.448 22 3V21C22 21.552 21.552 22 21 22H3C2.448 22 2 21.552 2 21V3C2 2.448 2.448 2 3 2H12Z");
  stroke: none;
}

</style>
