<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtr_d0o8k"/><path class="vxlz0wo_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-20" {...props}></Icon>
<style>
:global(.dtr_d0o8k) {
  fill: currentColor;
  d: path("M7 17v5h10v-5z");
}

:global(.vxlz0wo_h) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v13h10z");
}

</style>
