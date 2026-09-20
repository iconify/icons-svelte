<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pf60eubcf"/><path class="mzs9lvbbs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:stuck-agent-outline-regular" {...props}></Icon>
<style>
:global(.mzs9lvbbs) {
  d: path("M19.5 4v16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pf60eubcf) {
  d: path("M11.32 7a5.5 5.5 0 1 1 -4.64 0");
}

</style>
