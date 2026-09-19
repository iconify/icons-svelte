<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgetemsit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-battery-charging-full" {...props}></Icon>
<style>
:global(.pgetemsit) {
  fill: currentColor;
  d: path("M17 4h-3V2h-4v2H7v18h10zm-6 16v-5.5H9L13 7v5.5h2z");
}

</style>
