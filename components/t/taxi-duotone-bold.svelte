<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qp882rbfj"/><path class="h03wmtogt"/><path class="yo-dkgbus"/><path class="sqwju3bsh"/><path class="du3agkbjb"/><path class="fquh7rbnp"/><path class="ttwfj4bjd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:taxi-duotone-bold" {...props}></Icon>
<style>
:global(.du3agkbjb) {
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fquh7rbnp) {
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.h03wmtogt) {
  fill: currentColor;
  d: path("M5 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qp882rbfj) {
  fill: currentColor;
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sqwju3bsh) {
  d: path("M2 16V8.5h4L9.5 5h5L18 8.5h4V16Z");
}

:global(.ttwfj4bjd) {
  d: path("M9.5 5V2h5v3");
}

:global(.yo-dkgbus) {
  fill: currentColor;
  d: path("M15 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
