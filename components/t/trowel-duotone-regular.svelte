<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hzbhvwzxd"/><path class="bgmcrbcdd"/><path class="zh6-txvmz"/><path class="sfjortb-o"/><path class="iuwfsxlzr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trowel-duotone-regular" {...props}></Icon>
<style>
:global(.bgmcrbcdd) {
  fill: currentColor;
  d: path("M10 4h4v3h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hzbhvwzxd) {
  fill: currentColor;
  d: path("M7 12h10c0 4 -3 7 -5 9 -2 -2 -5 -5 -5 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iuwfsxlzr) {
  d: path("M10 4h4v3h-4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sfjortb-o) {
  d: path("M12 7v5");
}

:global(.zh6-txvmz) {
  d: path("M7 12h10c0 4 -3 7 -5 9 -2 -2 -5 -5 -5 -9");
}

</style>
