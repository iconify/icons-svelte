<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ye25mobvf"/><path class="cxzkdrccx"/><path class="qcrwpxioe"/><path class="tklvt-buk"/><path class="wnnpn6bje"/><path class="znfuzdoyp"/><path class="mt0duqbnk"/><path class="luzoskb2e"/><path class="l1lmw_bdv"/><path class="saj3disjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stargazing-duotone-regular" {...props}></Icon>
<style>
:global(.cxzkdrccx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l1lmw_bdv) {
  d: path("M13 11h6");
}

:global(.luzoskb2e) {
  d: path("M16 8v6");
}

:global(.mt0duqbnk) {
  d: path("M4 6h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qcrwpxioe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 8v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.saj3disjq) {
  d: path("M3 20c4 -3 14 -3 18 0");
}

:global(.tklvt-buk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 11h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wnnpn6bje) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20c4 -3 14 -3 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ye25mobvf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.znfuzdoyp) {
  d: path("M7 3v6");
}

</style>
