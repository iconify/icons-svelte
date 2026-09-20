<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cif7hjyui"/><path class="snzt8gbnb"/><path class="q5fdyummg"/><path class="qjn5qnbcp"/><path class="ituxlackf"/><path class="u_w_0bb2y"/><path class="pek-tswzf"/><path class="dak2_9b1i"/><path class="hxoe7gx5p"/><path class="fyt8fyb5h"/><path class="x-egzxztr"/><path class="eg0ecwbhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:score-distribution-duotone-regular" {...props}></Icon>
<style>
:global(.cif7hjyui) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 13v4");
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

:global(.hxoe7gx5p) {
  d: path("M12 5v12");
}

:global(.ituxlackf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 13v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pek-tswzf) {
  d: path("M4 13v4");
}

:global(.q5fdyummg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qjn5qnbcp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.snzt8gbnb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 9v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u_w_0bb2y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x-egzxztr) {
  d: path("M20 13v4");
}

</style>
