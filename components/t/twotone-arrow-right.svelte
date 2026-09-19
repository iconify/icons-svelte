<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsmckdbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-arrow-right" {...props}></Icon>
<style>
:global(.dsmckdbwm) {
  fill: currentColor;
  d: path("m10 17l5-5l-5-5z");
}

</style>
