<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ja0_o1hya"/><path class="as36babgs"/><path class="natztjpnv"/><path class="k3tsosaqu"/><path class="qdx3_bbpq"/><path class="ftqzjnb8u"/><path class="a23llpbrh"/><path class="ta7smn7pq"/><path class="s09jr7bxh"/><path class="gj9xsebsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sea-level-duotone-thin" {...props}></Icon>
<style>
:global(.a23llpbrh) {
  d: path("M4 3h4");
}

:global(.as36babgs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.gj9xsebsr) {
  d: path("m9 20 3 -3 3 3 3 -3 3 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ja0_o1hya) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k3tsosaqu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.natztjpnv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qdx3_bbpq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 20 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s09jr7bxh) {
  d: path("m9 15 3 -3 3 3 3 -3 3 3");
}

:global(.ta7smn7pq) {
  d: path("M4 9h4");
}

</style>
