<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b_li-tbgg"/><path class="hafotv34s"/><path class="g04xkmgbk"/><path class="qcu95-bhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sleeper-duotone-regular" {...props}></Icon>
<style>
:global(.b_li-tbgg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g04xkmgbk) {
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
}

:global(.hafotv34s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 4h4l-4 4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
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
