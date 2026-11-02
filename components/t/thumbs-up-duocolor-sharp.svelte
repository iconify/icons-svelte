<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k-ffe5bqu"/><path class="py6rgdbwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thumbs-up-duocolor-sharp" {...props}></Icon>
<style>
:global(.k-ffe5bqu) {
  stroke-opacity: 0.4;
  d: path("M7 10H3v11h4z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.py6rgdbwd) {
  d: path("M7 10a4 4 0 0 0 4-4V5a2 2 0 1 1 4 0v5h6v4l-2 7H7");
}

</style>
