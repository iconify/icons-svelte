<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jow_-gbao"/><path class="ygiw2ubfa"/><path class="yxvqngjob"/><path class="xq0-wskxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:yalp" {...props}></Icon>
<style>
:global(.jow_-gbao) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.76 8.74L21.77 24l-5-5l17.9-9.95a6.1 6.1 0 0 1 1.73-.64a2.06 2.06 0 0 1 1.36.33");
}

:global(.xq0-wskxp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.77 24l16 15.24c-.78.71-2.1.25-3.07-.29L16.81 29Z");
}

:global(.ygiw2ubfa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.76 8.74a3.6 3.6 0 0 1 .89 2.85v24.82a3.54 3.54 0 0 1-.9 2.83L21.77 24l16-15.26Z");
}

:global(.yxvqngjob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.81 19l5 5l-5 5l-5.88-3.26c-2.11-1.17-2.1-2.4 0-3.56z");
}

</style>
