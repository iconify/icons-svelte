<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykjv5hbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-chat-bubble" {...props}></Icon>
<style>
:global(.ykjv5hbpp) {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h16z");
}

</style>
