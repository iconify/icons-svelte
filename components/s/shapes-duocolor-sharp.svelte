<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kp42mccma"/><path class="zd0mcdxvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shapes-duocolor-sharp" {...props}></Icon>
<style>
:global(.kp42mccma) {
  stroke-opacity: 0.4;
  d: path("m8 4l4 6H4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zd0mcdxvh) {
  d: path("M3 15h6v6H3Zm10 2a4 4 0 1 0 8 0a4 4 0 0 0-8 0");
}

</style>
