<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a7giyacqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:zoom-in-16-filled" {...props}></Icon>
<style>
:global(.a7giyacqh) {
  fill: currentColor;
  d: path("M6.5 1a5.5 5.5 0 0 1 4.227 9.02l3.127 3.127a.5.5 0 1 1-.707.707l-3.127-3.127A5.5 5.5 0 1 1 6.5 1m0 3a.5.5 0 0 0-.5.5V6H4.5a.5.5 0 0 0 0 1H6v1.5a.5.5 0 0 0 1 0V7h1.5a.5.5 0 0 0 0-1H7V4.5a.5.5 0 0 0-.5-.5");
}

</style>
