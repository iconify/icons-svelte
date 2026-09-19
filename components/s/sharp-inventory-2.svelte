<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qnxdnwbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-inventory-2" {...props}></Icon>
<style>
:global(.qnxdnwbqt) {
  fill: currentColor;
  d: path("M2 2v6.7h1V22h18V8.7h1V2zm13 12H9v-2h6zm5-7H4V4h16z");
}

</style>
