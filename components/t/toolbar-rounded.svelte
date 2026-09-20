<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6dq52byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:toolbar-rounded" {...props}></Icon>
<style>
:global(.v6dq52byi) {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19v-9h18v9q0 .825-.587 1.413T19 21zM3 8V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v3z");
}

</style>
