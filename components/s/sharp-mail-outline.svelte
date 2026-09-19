<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqn2vnbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-mail-outline" {...props}></Icon>
<style>
:global(.aqn2vnbqm) {
  fill: currentColor;
  d: path("M22 4H2.01L2 20h20zm-2 14H4V8l8 5l8-5zm-8-7L4 6h16z");
}

</style>
