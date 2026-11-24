<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wp820wbfk"/><path class="efbd2xbhc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skyscraper-duocolor-round" {...props}></Icon>
<style>
:global(.efbd2xbhc) {
  d: path("M3 21h18M8 21V6a1 1 0 0 1 1-1h1V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v1h1a1 1 0 0 1 1 1v15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wp820wbfk) {
  stroke-opacity: 0.4;
  d: path("M12 8h.01M12 12h.01M12 16h.01");
}

</style>
