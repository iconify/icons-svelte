<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rq77ywb_t"/><path class="ka65bt2el"/><path class="z6iz6metx"/><path class="nu4ml-bmq"/><path class="kc811hbmp"/><path class="hk697hhuu"/><path class="gwnaabclj"/><path class="ey3upmocl"/><path class="yazo7scbq"/><path class="jms1xqp8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:timer-duotone-bold" {...props}></Icon>
<style>
:global(.ey3upmocl) {
  d: path("M14 14h4");
}

:global(.gwnaabclj) {
  d: path("M12 9v5");
}

:global(.hk697hhuu) {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
}

:global(.ka65bt2el) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kc811hbmp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nu4ml-bmq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rq77ywb_t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

:global(.z6iz6metx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 14h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
