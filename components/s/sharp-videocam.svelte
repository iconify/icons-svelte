<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efk3_mi9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-videocam" {...props}></Icon>
<style>
:global(.efk3_mi9r) {
  fill: currentColor;
  d: path("M17 10.5V6H3v12h14v-4.5l4 4v-11z");
}

</style>
