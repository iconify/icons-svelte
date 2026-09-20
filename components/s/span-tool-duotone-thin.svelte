<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h0zlamt3c"/><path class="mlfxoobfi"/><path class="yt28ykbai"/><path class="uzrr--bsw"/><path class="pldoi_k0z"/><path class="s-mi-tbrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:span-tool-duotone-thin" {...props}></Icon>
<style>
:global(.h0zlamt3c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 5h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mlfxoobfi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pldoi_k0z) {
  d: path("M7 11h11");
}

:global(.s-mi-tbrv) {
  d: path("M10 17h11");
}

:global(.uzrr--bsw) {
  d: path("M3 5h9");
}

:global(.yt28ykbai) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 17h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
