<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8ivdvbnd"/><path class="zmp46gb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-30" {...props}></Icon>
<style>
:global(.p8ivdvbnd) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v11h10z");
}

:global(.zmp46gb-r) {
  fill: currentColor;
  d: path("M7 15v7h10v-7z");
}

</style>
