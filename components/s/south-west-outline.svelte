<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxwgrgb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:south-west-outline" {...props}></Icon>
<style>
:global(.sxwgrgb_u) {
  fill: currentColor;
  d: path("M5 19V9h2v6.6L18.6 4L20 5.4L8.4 17H15v2z");
}

</style>
