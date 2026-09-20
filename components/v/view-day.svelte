<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta2dzx0fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-day" {...props}></Icon>
<style>
:global(.ta2dzx0fl) {
  fill: currentColor;
  d: path("M3 20v-2h18v2zM3 6V4h18v2zm2 10q-.825 0-1.412-.587T3 14v-4q0-.825.588-1.412T5 8h14q.825 0 1.413.588T21 10v4q0 .825-.587 1.413T19 16z");
}

</style>
