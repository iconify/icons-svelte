<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nrlkc9bnf"/><path class="rbe8j9b-u"/><path class="dvoob7u7j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:warm-standby-outline-thin" {...props}></Icon>
<style>
:global(.dvoob7u7j) {
  d: path("M13.5 9.5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nrlkc9bnf) {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.rbe8j9b-u) {
  d: path("M10.5 9.5v5");
}

</style>
