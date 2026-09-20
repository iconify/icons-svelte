<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcb9_2bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:timer-5-shutter" {...props}></Icon>
<style>
:global(.wcb9_2bqt) {
  fill: currentColor;
  d: path("M8 19v-3h6v-2.5H8V5h9v3h-6v2.5h4q.825 0 1.413.588T17 12.5V16q0 1.25-.875 2.125T14 19z");
}

</style>
