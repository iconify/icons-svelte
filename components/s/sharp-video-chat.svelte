<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gyvqrbb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-video-chat" {...props}></Icon>
<style>
:global(.gyvqrbb9m) {
  fill: currentColor;
  d: path("M2 2v20l4-4h16V2zm15 11l-2-1.99V14H7V6h8v2.99L17 7z");
}

</style>
