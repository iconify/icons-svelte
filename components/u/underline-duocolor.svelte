<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zaxhg3e5y"/><path class="ps0mh7bvo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:underline-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ps0mh7bvo) {
  d: path("M8 5v6a4 4 0 1 0 8 0V5");
}

:global(.zaxhg3e5y) {
  stroke-opacity: 0.4;
  d: path("M6 19h12");
}

</style>
