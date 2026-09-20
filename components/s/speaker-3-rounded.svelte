<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le4omjblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:speaker-3-rounded" {...props}></Icon>
<style>
:global(.le4omjblj) {
  fill: currentColor;
  d: path("M7 21q-1.25 0-2.125-.875T4 18V5q0-1.25.875-2.125T7 2h10q1.25 0 2.125.875T20 5v13q0 1.25-.875 2.125T17 21h-1q0 .425-.288.713T15 22H9q-.425 0-.712-.288T8 21z");
}

</style>
