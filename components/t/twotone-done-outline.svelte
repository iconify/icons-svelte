<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ercz-pbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-done-outline" {...props}></Icon>
<style>
:global(.ercz-pbif) {
  fill: currentColor;
  d: path("m19.77 4.93l1.4 1.4L8.43 19.07l-5.6-5.6l1.4-1.4l4.2 4.2zm0-2.83L8.43 13.44l-4.2-4.2L0 13.47l8.43 8.43L24 6.33z");
}

</style>
