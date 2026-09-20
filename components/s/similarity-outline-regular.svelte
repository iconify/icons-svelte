<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j1y852r1k"/><path class="jbwvw6voa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:similarity-outline-regular" {...props}></Icon>
<style>
:global(.j1y852r1k) {
  d: path("m9 5 5 5 -5 5 -5 -5Z");
}

:global(.jbwvw6voa) {
  d: path("m15 9 5 5 -5 5 -5 -5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
