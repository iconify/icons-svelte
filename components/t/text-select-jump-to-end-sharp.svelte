<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udd6gdcdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-select-jump-to-end-sharp" {...props}></Icon>
<style>
:global(.udd6gdcdc) {
  fill: currentColor;
  d: path("M3 21v-2h2v2zM3 5V3h2v2zm4 16v-2h2v2zM7 5V3h2v2zm4 16v-2h2v2zm4 0v-2h2v2zm0-16V3h2v2zm4 16V3h2v18zm-9-5l-1.4-1.4l1.575-1.6H3v-2h7.175L8.6 9.4L10 8l4 4zm1-11V3h2v2z");
}

</style>
