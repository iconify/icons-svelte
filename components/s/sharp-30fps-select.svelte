<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4guqv2dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-30fps-select" {...props}></Icon>
<style>
:global(.j4guqv2dh) {
  fill: currentColor;
  d: path("M4 4v2h5v2H5v2h4v2H4v2h7V4zm9 0h7v10h-7zm5 2h-3v6h3zM5 22H3v-5h2zm4 0H7v-5h2zm4 0h-2v-5h2zm8 0h-6v-5h6z");
}

</style>
