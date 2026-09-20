<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tqek15bkw"/><path class="rr5s23bmj"/><path class="d1sql1bsn"/><path class="z0jk47bno"/><path class="hz3am-5yp"/><path class="hk697hhuu"/><path class="yazo7scbq"/><path class="jms1xqp8l"/><path class="ikiprn9sq"/><path class="dc7kvgdwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:time-arrow-left-duotone-thin" {...props}></Icon>
<style>
:global(.d1sql1bsn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dc7kvgdwc) {
  d: path("M11.5 11.5 9 14l2.5 2.5");
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

:global(.hz3am-5yp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 11.5 9 14l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
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

:global(.yazo7scbq) {
  d: path("M12 3v3");
}

:global(.z0jk47bno) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
