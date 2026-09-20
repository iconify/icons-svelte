<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g04xkmgbk"/><path class="qcu95-bhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sleeper-outline-regular" {...props}></Icon>
<style>
:global(.g04xkmgbk) {
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qcu95-bhb) {
  d: path("M15 4h4l-4 4h4");
}

</style>
