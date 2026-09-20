<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0773wboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:send" {...props}></Icon>
<style>
:global(.l0773wboh) {
  fill: currentColor;
  d: path("M3 20v-6l8-2l-8-2V4l19 8z");
}

</style>
