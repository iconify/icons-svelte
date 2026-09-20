<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ppivcbbzp"/><path class="t87ohzbeq"/><path class="qjej79sen"/><path class="qd0z4jbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wait-until-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ppivcbbzp) {
  d: path("M5 4v16");
}

:global(.qd0z4jbov) {
  d: path("M16.5 9.5 19 12l-2.5 2.5");
}

:global(.qjej79sen) {
  d: path("M12.5 12H17");
}

:global(.t87ohzbeq) {
  d: path("M9 4v16");
}

</style>
