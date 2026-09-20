<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sgfpn4bih"/><path class="q63x0etiq"/><path class="ixxv1jyxb"/><path class="afbeh5blb"/><path class="hte-ztbfo"/><path class="qr4axhbjr"/><path class="pek-tswzf"/><path class="dak2_9b1i"/><path class="hxoe7gx5p"/><path class="fyt8fyb5h"/><path class="x-egzxztr"/><path class="eg0ecwbhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:score-distribution-duotone-bold" {...props}></Icon>
<style>
:global(.afbeh5blb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dak2_9b1i) {
  d: path("M8 9v8");
}

:global(.eg0ecwbhj) {
  d: path("M3 19.5h18");
}

:global(.fyt8fyb5h) {
  d: path("M16 9v8");
}

:global(.hte-ztbfo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hxoe7gx5p) {
  d: path("M12 5v12");
}

:global(.ixxv1jyxb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pek-tswzf) {
  d: path("M4 13v4");
}

:global(.q63x0etiq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qr4axhbjr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sgfpn4bih) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x-egzxztr) {
  d: path("M20 13v4");
}

</style>
