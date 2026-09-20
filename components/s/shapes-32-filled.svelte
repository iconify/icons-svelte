<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i6ion_5kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:shapes-32-filled" {...props}></Icon>
<style>
:global(.i6ion_5kc) {
  fill: currentColor;
  d: path("M3 12a9 9 0 0 1 17.876-1.5H16.5a6 6 0 0 0-6 6v4.376C6.243 20.16 3 16.459 3 12m9 4.5a4.5 4.5 0 0 1 4.5-4.5h8a4.5 4.5 0 0 1 4.5 4.5v8a4.5 4.5 0 0 1-4.5 4.5h-8a4.5 4.5 0 0 1-4.5-4.5z");
}

</style>
