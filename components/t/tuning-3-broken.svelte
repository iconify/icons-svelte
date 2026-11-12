<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="h_tsn8bxt"/><circle class="imrhgbc8c"/><circle class="qbe_3qbje"/><path class="qkb6nu2hb"/><path class="qpr92sbth"/><path class="ml0f3uy3t"/><path class="j3t_yv6ja"/><path class="n9mrrlban"/><path class="cl5kvxb6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tuning-3-broken" {...props}></Icon>
<style>
:global(.cl5kvxb6w) {
  d: path("M12 10V7.5M12 5.5V5");
}

:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.imrhgbc8c) {
  cx: 20px;
  cy: 14px;
  r: 2px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j3t_yv6ja) {
  d: path("M20 19L20 16");
}

:global(.ml0f3uy3t) {
  d: path("M12 19V14");
}

:global(.n9mrrlban) {
  d: path("M4 5V7.66667");
}

:global(.qbe_3qbje) {
  cx: 4px;
  cy: 10px;
  r: 2px;
}

:global(.qkb6nu2hb) {
  d: path("M4 17.5V19M4 12V14.75");
}

:global(.qpr92sbth) {
  d: path("M20 6.5V5M20 12V9.25");
}

</style>
