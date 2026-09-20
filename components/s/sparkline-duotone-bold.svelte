<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n4jvs51cl"/><path class="buwnnz1fg"/><path class="zm2kbsbyq"/><path class="hhryeubon"/><path class="oi0elobpe"/><path class="wpfzotbdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sparkline-duotone-bold" {...props}></Icon>
<style>
:global(.buwnnz1fg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 21h5v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hhryeubon) {
  d: path("M3 8V3h5");
}

:global(.n4jvs51cl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8V3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oi0elobpe) {
  d: path("M16 21h5v-5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wpfzotbdn) {
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
}

:global(.zm2kbsbyq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 16 4 -4 3 3 4 -4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
