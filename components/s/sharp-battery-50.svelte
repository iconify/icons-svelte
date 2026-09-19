<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e850otbxv"/><path class="t-y0e6kia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-50" {...props}></Icon>
<style>
:global(.e850otbxv) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v9h10z");
}

:global(.t-y0e6kia) {
  fill: currentColor;
  d: path("M7 13v9h10v-9z");
}

</style>
