<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="crc8axbhg"/><path class="i1wyv5kqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:usb-hub-duocolor-sharp" {...props}></Icon>
<style>
:global(.crc8axbhg) {
  stroke-opacity: 0.4;
  d: path("M7 17h2m6 0h2");
}

:global(.i1wyv5kqc) {
  d: path("M3 13h18v8H3ZM9 3h6v4H9Zm3 4v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
