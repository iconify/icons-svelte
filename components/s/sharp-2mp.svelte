<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kklyh2i4u"/><path class="k4n51fjcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-2mp" {...props}></Icon>
<style>
:global(.k4n51fjcs) {
  fill: currentColor;
  d: path("M15 14h1.5v1.5H15z");
}

:global(.kklyh2i4u) {
  fill: currentColor;
  d: path("M3 3v18h18V3zm7 5h3V7h-3V5.5h4.5V9h-3v1h3v1.5H10zm2.5 10.5H11V14h-1v3H8.5v-3h-1v4.5H6v-6h6.5zM18 17h-3v1.5h-1.5v-6H18z");
}

</style>
