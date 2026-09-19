<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="celeutb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-featured-video" {...props}></Icon>
<style>
:global(.celeutb3k) {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-11 9H3V5h9z");
}

</style>
