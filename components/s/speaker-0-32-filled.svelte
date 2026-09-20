<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dpnaw-32d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:speaker-0-32-filled" {...props}></Icon>
<style>
:global(.dpnaw-32d) {
  fill: currentColor;
  d: path("M18 5.433c0-1.398-1.742-2.036-2.645-.97l-4.086 4.83A2 2 0 0 1 9.743 10H6a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h3.743a2 2 0 0 1 1.526.708l4.086 4.829c.902 1.066 2.645.428 2.645-.97z");
}

</style>
