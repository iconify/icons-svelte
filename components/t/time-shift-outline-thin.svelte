<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="lcdiu5g_w"/><path class="ikiprn9sq"/><path class="xiowoubxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-shift-outline-thin" {...props}></Icon>
<style>
:global(.hk697hhuu) {
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
}

:global(.lcdiu5g_w) {
  d: path("M9 11v6");
}

:global(.xiowoubxu) {
  d: path("M12.5 11.5 15 14l-2.5 2.5");
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

</style>
