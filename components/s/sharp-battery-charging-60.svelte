<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyow0wb0a"/><path class="ipfvtgbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-charging-60" {...props}></Icon>
<style>
:global(.ipfvtgbrq) {
  fill: currentColor;
  d: path("M13 12.5h2L11 20v-5.5H9l1.87-3.5H7v11h10V11h-4z");
}

:global(.lyow0wb0a) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v7h3.87L13 7v4h4z");
}

</style>
