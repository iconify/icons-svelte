<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yogr3rmvf"/><path class="y3fc0ljog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-80" {...props}></Icon>
<style>
:global(.y3fc0ljog) {
  fill: currentColor;
  d: path("M7 9v13h10V9z");
}

:global(.yogr3rmvf) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v5h10z");
}

</style>
