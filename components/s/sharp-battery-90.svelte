<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o89yxue8q"/><path class="ler3fnomh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-90" {...props}></Icon>
<style>
:global(.ler3fnomh) {
  fill: currentColor;
  d: path("M7 8v14h10V8z");
}

:global(.o89yxue8q) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v4h10z");
}

</style>
