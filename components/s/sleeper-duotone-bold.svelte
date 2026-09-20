<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eoxc8ac-a"/><path class="wixq0sb-e"/><path class="g04xkmgbk"/><path class="qcu95-bhb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sleeper-duotone-bold" {...props}></Icon>
<style>
:global(.eoxc8ac-a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g04xkmgbk) {
  d: path("M12.54 7.56a6 6 0 1 1 -5.08 0");
}

:global(.qcu95-bhb) {
  d: path("M15 4h4l-4 4h4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wixq0sb-e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 4h4l-4 4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
