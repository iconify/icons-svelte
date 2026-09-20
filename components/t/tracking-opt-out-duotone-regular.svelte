<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q4dbwx7ej"/><path class="kti78mmln"/><path class="qn27zxvzh"/><path class="jiq_guqwb"/><path class="yix-58bnj"/><path class="moha5wbmp"/><path class="lxtc-wp5b"/><path class="s-cqkabbd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tracking-opt-out-duotone-regular" {...props}></Icon>
<style>
:global(.jiq_guqwb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 10 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kti78mmln) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lxtc-wp5b) {
  d: path("m10 10 4 4");
}

:global(.moha5wbmp) {
  d: path("M22 12a12.5 12.5 0 0 1 -20 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q4dbwx7ej) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qn27zxvzh) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s-cqkabbd) {
  d: path("m14 10 -4 4");
}

:global(.yix-58bnj) {
  d: path("M2 12a12.5 12.5 0 0 1 20 0");
}

</style>
