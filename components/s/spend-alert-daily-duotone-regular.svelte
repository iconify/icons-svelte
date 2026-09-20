<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ro1o_8s6w"/><path class="zmp0zuf9j"/><path class="k70w93buq"/><path class="f4yp5uw0u"/><path class="f73i47bnv"/><path class="fxnzc9b-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:spend-alert-daily-duotone-regular" {...props}></Icon>
<style>
:global(.f4yp5uw0u) {
  d: path("M14 18.5a2 2 0 0 1 -4 0");
}

:global(.f73i47bnv) {
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.fxnzc9b-v) {
  d: path("M12 9v4");
}

:global(.k70w93buq) {
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ro1o_8s6w) {
  fill: currentColor;
  d: path("M6 15v-5a6 6 0 0 1 12 0v5l2.5 2.5h-17z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zmp0zuf9j) {
  fill: currentColor;
  d: path("M9 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
