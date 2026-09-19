<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnp3t2qtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-change-history" {...props}></Icon>
<style>
:global(.hnp3t2qtv) {
  fill: currentColor;
  d: path("M12 7.77L18.39 18H5.61zM12 4L2 20h20z");
}

</style>
