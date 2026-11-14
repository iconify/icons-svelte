<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_309sbqs"/><path class="pz6-j35rt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:vortex-mixer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n_309sbqs) {
  d: path("M6.5 15.5h11a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-11a3 3 0 0 1-3-3a3 3 0 0 1 3-3");
}

:global(.pz6-j35rt) {
  d: path("M10 2.5v11a2 2 0 0 0 4 0v-11M6.5 6q-1.5 3 0 6m11-6q1.5 3 0 6");
}

</style>
