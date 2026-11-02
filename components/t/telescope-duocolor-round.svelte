<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nuvbu6bqy"/><path class="j5ogwdeze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:telescope-duocolor-round" {...props}></Icon>
<style>
:global(.j5ogwdeze) {
  d: path("m10 7l6-3a2.236 2.236 0 0 1 2 4L8 13a2.236 2.236 0 0 1-2-4zm4-2l2 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nuvbu6bqy) {
  stroke-opacity: 0.4;
  d: path("M12 11L7 21m5-10l5 10");
}

</style>
