<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oa__skhab"/><path class="a-ib5crgb"/><path class="w8h2wrjnp"/><path class="g02azz8fb"/><path class="kdee3bb5f"/><path class="w9rv6acfm"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="lcdiu5g_w"/><path class="ikiprn9sq"/><path class="xiowoubxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-shift-duotone-regular" {...props}></Icon>
<style>
:global(.a-ib5crgb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g02azz8fb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hk697hhuu) {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
}

:global(.kdee3bb5f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lcdiu5g_w) {
  d: path("M9 11v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oa__skhab) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w8h2wrjnp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w9rv6acfm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 11.5 15 14l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xiowoubxu) {
  d: path("M12.5 11.5 15 14l-2.5 2.5");
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
