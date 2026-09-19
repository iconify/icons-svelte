<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5s_e9bbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-repeat-one-on" {...props}></Icon>
<style>
:global(.c5s_e9bbh) {
  fill: currentColor;
  d: path("M21 1H3c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m-2 18H7v3l-4-4l4-4v3h10v-4h2zm-9-8.5V9h3v6h-1.5v-4.5zm7-.5V7H7v4H5V5h12V2l4 4z");
}

</style>
