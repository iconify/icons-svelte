<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfi4qnq1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:timer-5-shutter-outline" {...props}></Icon>
<style>
:global(.kfi4qnq1m) {
  fill: currentColor;
  d: path("M8 19v-3h6v-2.5H8V5h9v3h-6v2.5h3q1.25 0 2.125.875T17 13.5V16q0 1.25-.875 2.125T14 19z");
}

</style>
