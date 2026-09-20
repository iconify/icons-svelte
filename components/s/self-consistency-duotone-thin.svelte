<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bguwb2kyq"/><path class="s2ztwmbwx"/><path class="t-3s33n5f"/><path class="bcz5ov0ne"/><path class="ds000fbnl"/><path class="bj2hlhbfp"/><path class="ukjt4fb6s"/><path class="ids981bkm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:self-consistency-duotone-thin" {...props}></Icon>
<style>
:global(.bcz5ov0ne) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 11 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bguwb2kyq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bj2hlhbfp) {
  d: path("M3 12h12");
}

:global(.ds000fbnl) {
  d: path("M3 7h12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ids981bkm) {
  d: path("m17 11 2 2 3 -3");
}

:global(.s2ztwmbwx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t-3s33n5f) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ukjt4fb6s) {
  d: path("M3 17h12");
}

</style>
