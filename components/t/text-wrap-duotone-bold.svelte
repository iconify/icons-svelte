<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="ewn3iubfv"/><path class="t1ep0ebko"/><path class="gq5kn0epi"/><path class="xgrfb-bqu"/><path class="he7cpnbxn"/><path class="ky10s_bai"/><path class="ru0la3bku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-wrap-duotone-bold" {...props}></Icon>
<style>
:global(.ewn3iubfv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gq5kn0epi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.5 12.5 10 15l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.he7cpnbxn) {
  d: path("M3 12h14");
}

:global(.khksl7boy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ky10s_bai) {
  d: path("M17 12v3h-7");
}

:global(.ru0la3bku) {
  d: path("M12.5 12.5 10 15l2.5 2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t1ep0ebko) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 12v3h-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
