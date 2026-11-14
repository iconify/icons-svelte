<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c18cyra9h"/><path class="unf0dck7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sprint" {...props}></Icon>
<style>
:global(.c18cyra9h) {
  d: path("M15 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m.5 3.5L11 13l3 3l-2 5m-1-8l-3.5 3l-3.5-.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.unf0dck7i) {
  d: path("m8 10l3.5-2.5h4l3 4l2.5-1M2.5 8h4m-4 3.5h3");
}

</style>
