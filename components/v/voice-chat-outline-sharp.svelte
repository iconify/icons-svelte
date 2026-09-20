<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dugwsiozx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:voice-chat-outline-sharp" {...props}></Icon>
<style>
:global(.dugwsiozx) {
  fill: currentColor;
  d: path("M6 11h1.5V9H6zm2.5 2H10V7H8.5zm2.75 2h1.5V5h-1.5zM14 13h1.5V7H14zm2.5-2H18V9h-1.5zM2 22V2h20v16H6zm3.15-6H20V4H4v13.125zM4 16V4z");
}

</style>
