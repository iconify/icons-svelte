<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffns4ybyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-featured-play-list" {...props}></Icon>
<style>
:global(.ffns4ybyp) {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-11 8H3V9h9zm0-4H3V5h9z");
}

</style>
