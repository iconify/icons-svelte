<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ikx5r_b7y"/><path class="s3jkn35cv"/><path class="yea3zvbmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:verified-badge-duotone-regular" {...props}></Icon>
<style>
:global(.ikx5r_b7y) {
  fill: currentColor;
  d: path("M9 4h6l5 5v6l-5 5H9l-5 -5V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s3jkn35cv) {
  d: path("M9 4h6l5 5v6l-5 5H9l-5 -5V9Z");
}

:global(.yea3zvbmx) {
  d: path("m8 12 3 3 5 -5");
}

</style>
