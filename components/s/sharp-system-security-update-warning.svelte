<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e41ip5b0d"/><path class="w89-xcbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-system-security-update-warning" {...props}></Icon>
<style>
:global(.e41ip5b0d) {
  fill: currentColor;
  d: path("M11 15h2v2h-2zm0-8h2v6h-2z");
}

:global(.w89-xcbdt) {
  fill: currentColor;
  d: path("M5.01 1v22H19V1zM17 18H7V6h10z");
}

</style>
