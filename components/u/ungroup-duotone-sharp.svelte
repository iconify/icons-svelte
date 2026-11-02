<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bc6akkb6o"/><path class="z2c-hu7is"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ungroup-duotone-sharp" {...props}></Icon>
<style>
:global(.bc6akkb6o) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 5v5H5V5Zm7 9v5h-7v-5Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.z2c-hu7is) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 5h7v5H5zm7 9h7v5h-7z");
}

</style>
