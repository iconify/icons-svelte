<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsea1pbos"/><path class="ph8xawbhr"/><path class="kq4t-bc5h"/><path class="nnmb7abbp"/><path class="x6ipc2vyr"/><path class="xx4d75shr"/><path class="zuquf0b8s"/><path class="fcstqn4mf"/><path class="sjot3p-qh"/><path class="aoxrbobxu"/><path class="qrln8gb_a"/><path class="ktpncgb0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:websocket-close-duotone-regular" {...props}></Icon>
<style>
:global(.aoxrbobxu) {
  d: path("M14 8h4");
}

:global(.fcstqn4mf) {
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kq4t-bc5h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ktpncgb0v) {
  d: path("M10 16H6");
}

:global(.nnmb7abbp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ph8xawbhr) {
  fill: currentColor;
  d: path("M18 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qrln8gb_a) {
  d: path("M18 16h-4");
}

:global(.rsea1pbos) {
  fill: currentColor;
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sjot3p-qh) {
  d: path("M6 8h4");
}

:global(.x6ipc2vyr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xx4d75shr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 16H6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zuquf0b8s) {
  d: path("M2 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
