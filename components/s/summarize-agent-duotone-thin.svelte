<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sve5l4brn"/><path class="fdrbywb2q"/><path class="vku7vnm4c"/><path class="g2-e3wkpa"/><path class="pxx-spbdi"/><path class="pi0o-3bfc"/><path class="ifhv18rgk"/><path class="t_kadbb9f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:summarize-agent-duotone-thin" {...props}></Icon>
<style>
:global(.fdrbywb2q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g2-e3wkpa) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 17h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ifhv18rgk) {
  d: path("M12 12h6");
}

:global(.pi0o-3bfc) {
  d: path("M12 7h9");
}

:global(.pxx-spbdi) {
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
}

:global(.sve5l4brn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7.5 8.83a3.5 3.5 0 1 1 -2.96 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t_kadbb9f) {
  d: path("M12 17h3");
}

:global(.vku7vnm4c) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
