<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-wgnhbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-carpenter" {...props}></Icon>
<style>
:global(.c-wgnhbbu) {
  fill: currentColor;
  d: path("M7 1.5L3.11 5.39l8.13 11.67l-1.41 1.41l4.24 4.24l7.07-7.07zm5.66 16.97l4.24-4.24l1.41 1.41l-4.24 4.24z");
}

</style>
