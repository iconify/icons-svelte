<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="c6xktm_ft"/><path class="izpdo2pcy"/><path class="pjf2x0mll"/><path class="xgrfb-bqu"/><path class="he7cpnbxn"/><path class="ky10s_bai"/><path class="ru0la3bku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-wrap-duotone-regular" {...props}></Icon>
<style>
:global(.be306ynmy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c6xktm_ft) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.he7cpnbxn) {
  d: path("M3 12h14");
}

:global(.izpdo2pcy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 12v3h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ky10s_bai) {
  d: path("M17 12v3h-7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pjf2x0mll) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 12.5 10 15l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ru0la3bku) {
  d: path("M12.5 12.5 10 15l2.5 2.5");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
