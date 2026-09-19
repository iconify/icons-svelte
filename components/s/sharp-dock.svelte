<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqx3kwm5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-dock" {...props}></Icon>
<style>
:global(.tqx3kwm5o) {
  fill: currentColor;
  d: path("M8 23h8v-2H8zM18 1.01L6 1v18h12zM16 15H8V5h8z");
}

</style>
