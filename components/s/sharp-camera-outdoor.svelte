<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoml00bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-camera-outdoor" {...props}></Icon>
<style>
:global(.xoml00bat) {
  fill: currentColor;
  d: path("M18 14v-2h-6v6h6v-2l2 1.06v-4.12zM12 3L4 9v12h16v-2H6v-9l6-4.5l6 4.5v1h2V9z");
}

</style>
