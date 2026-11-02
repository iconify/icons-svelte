<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n0h9zpbpw"/><path class="bs9lzgbhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wallbox-duotone-sharp" {...props}></Icon>
<style>
:global(.bs9lzgbhm) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h10v12H3Zm5 12v4h11v-6m-2-6h4v6h-4ZM9 6L6 9h4l-3 3");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.n0h9zpbpw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13 3v12H3V3Zm8 4v6h-4V7Z");
}

</style>
