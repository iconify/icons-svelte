<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrmo-yb4e"/><path class="o_5zgdb_v"/><path class="ju-vh8ntp"/><path class="nza1tnsqb"/><path class="ppivcbbzp"/><path class="t87ohzbeq"/><path class="qjej79sen"/><path class="qd0z4jbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wait-until-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ju-vh8ntp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.5 12H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrmo-yb4e) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nza1tnsqb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 9.5 19 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o_5zgdb_v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
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
