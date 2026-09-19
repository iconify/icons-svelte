<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lckuwvg-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-upload" {...props}></Icon>
<style>
:global(.lckuwvg-j) {
  fill: currentColor;
  d: path("M9 16h6v-6h4l-7-7l-7 7h4zm-4 2h14v2H5z");
}

</style>
