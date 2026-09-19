<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka37b4bpq"/><path class="udcimlx6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-charging-90" {...props}></Icon>
<style>
:global(.ka37b4bpq) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v4h5.47L13 7v1h4z");
}

:global(.udcimlx6s) {
  fill: currentColor;
  d: path("M13 12.5h2L11 20v-5.5H9L12.47 8H7v14h10V8h-4z");
}

</style>
