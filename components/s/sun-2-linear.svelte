<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="q1m15dbht"/><path class="x_jwp_bge"/><path class="a0gtrrbuj"/><path class="pw_kz6bsy"/><path class="p4-7k1g6n"/><path class="j8al4m6ce"/><path class="quhn2pcrw"/><path class="g8qpaoygp"/><path class="j9nl8b3qu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sun-2-linear" {...props}></Icon>
<style>
:global(.a0gtrrbuj) {
  d: path("M12 20V22");
}

:global(.g8qpaoygp) {
  d: path("M6.44531 17.5557L4.22309 19.7779");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8al4m6ce) {
  d: path("M19.7773 4.22217L17.5553 6.25375");
}

:global(.j9nl8b3qu) {
  d: path("M19.7773 19.7778L17.5553 17.5555");
}

:global(.p4-7k1g6n) {
  d: path("M22 12L20 12");
}

:global(.pw_kz6bsy) {
  d: path("M4 12L2 12");
}

:global(.q1m15dbht) {
  cx: 12px;
  cy: 12px;
  r: 5px;
}

:global(.quhn2pcrw) {
  d: path("M4.22266 4.22217L6.44467 6.25375");
}

:global(.x_jwp_bge) {
  d: path("M12 2V4");
}

</style>
