<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y5ir0ibok"/><path class="saw7fbc_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:security-key-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.saw7fbc_r) {
  d: path("M3 9a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm6 2v2m12-1h-2");
}

:global(.y5ir0ibok) {
  stroke-opacity: 0.4;
  d: path("M15 9h5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-5");
}

</style>
