<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpzmsjlui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:traffic-cone-fill-sharp" {...props}></Icon>
<style>
:global(.lpzmsjlui) {
  fill: currentColor;
  d: path("M15.677 9H8.323l1.749-4.371A1 1 0 0 1 11 4h2c.409 0 .777.249.928.629Zm2 5H6.323l1.2-3h8.954ZM3 21a1 1 0 0 1 0-2h1.323l1.2-3h12.954l1.2 3H21a1 1 0 0 1 0 2Z");
}

</style>
