<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg-n76gtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-video-label" {...props}></Icon>
<style>
:global(.kg-n76gtw) {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 13H3V5h18z");
}

</style>
