<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0ltr79xw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-crop-free" {...props}></Icon>
<style>
:global(.m0ltr79xw) {
  fill: currentColor;
  d: path("M3 19c0 1.1.9 2 2 2h4v-2H5v-4H3zM21 5c0-1.1-.9-2-2-2h-4v2h4v4h2zM5 5h4V3H5c-1.1 0-2 .9-2 2v4h2zm16 14v-4h-2v4h-4v2h4c1.1 0 2-.9 2-2");
}

</style>
