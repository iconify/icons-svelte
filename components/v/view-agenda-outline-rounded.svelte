<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-08iobmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-agenda-outline-rounded" {...props}></Icon>
<style>
:global(.t-08iobmc) {
  fill: currentColor;
  d: path("M5 11q-.825 0-1.412-.587T3 9V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v4q0 .825-.587 1.413T19 11zm0-2h14V5H5zm0 12q-.825 0-1.412-.587T3 19v-4q0-.825.588-1.412T5 13h14q.825 0 1.413.588T21 15v4q0 .825-.587 1.413T19 21zm0-2h14v-4H5zM5 5v4zm0 10v4z");
}

</style>
