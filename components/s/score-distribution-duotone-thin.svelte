<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="po7okpqgy"/><path class="au_o_7bss"/><path class="qir7x_1xu"/><path class="gk7zctbem"/><path class="q30q1h-zr"/><path class="dsax69fpp"/><path class="pek-tswzf"/><path class="dak2_9b1i"/><path class="hxoe7gx5p"/><path class="fyt8fyb5h"/><path class="x-egzxztr"/><path class="eg0ecwbhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:score-distribution-duotone-thin" {...props}></Icon>
<style>
:global(.au_o_7bss) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dak2_9b1i) {
  d: path("M8 9v8");
}

:global(.dsax69fpp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eg0ecwbhj) {
  d: path("M3 19.5h18");
}

:global(.fyt8fyb5h) {
  d: path("M16 9v8");
}

:global(.gk7zctbem) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hxoe7gx5p) {
  d: path("M12 5v12");
}

:global(.pek-tswzf) {
  d: path("M4 13v4");
}

:global(.po7okpqgy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q30q1h-zr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qir7x_1xu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x-egzxztr) {
  d: path("M20 13v4");
}

</style>
