<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjb6iab1i"/><path class="z0_8dacjp"/><path class="ks-di593s"/><path class="s1fkh9bhd"/><path class="xi2_tlb9u"/><path class="ftqzjnb8u"/><path class="a23llpbrh"/><path class="ta7smn7pq"/><path class="s09jr7bxh"/><path class="gj9xsebsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sea-level-duotone-regular" {...props}></Icon>
<style>
:global(.a23llpbrh) {
  d: path("M4 3h4");
}

:global(.ftqzjnb8u) {
  d: path("M6 3v18");
}

:global(.gj9xsebsr) {
  d: path("m9 20 3 -3 3 3 3 -3 3 3");
}

:global(.ks-di593s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rjb6iab1i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s09jr7bxh) {
  d: path("m9 15 3 -3 3 3 3 -3 3 3");
}

:global(.s1fkh9bhd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 15 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ta7smn7pq) {
  d: path("M4 9h4");
}

:global(.xi2_tlb9u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 20 3 -3 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z0_8dacjp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
