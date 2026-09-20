<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqek15bkw"/><path class="rr5s23bmj"/><path class="d1sql1bsn"/><path class="csbkh-b0j"/><path class="z0jk47bno"/><path class="wf1ku5bxc"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="lcdiu5g_w"/><path class="ikiprn9sq"/><path class="xiowoubxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-shift-duotone-thin" {...props}></Icon>
<style>
:global(.csbkh-b0j) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d1sql1bsn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

:global(.rr5s23bmj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tqek15bkw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.38 6.75a8 8 0 1 1 -6.76 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wf1ku5bxc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 11.5 15 14l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xiowoubxu) {
  d: path("M12.5 11.5 15 14l-2.5 2.5");
}

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

:global(.z0jk47bno) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
