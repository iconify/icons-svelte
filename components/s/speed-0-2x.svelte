<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0l-ilb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:speed-0-2x" {...props}></Icon>
<style>
:global(.m0l-ilb-d) {
  fill: currentColor;
  d: path("M3 17v-2h2v2zm3 0v-4q0-.825.588-1.412T8 11h2V9H6V7h4q.825 0 1.413.588T12 9v2q0 .825-.587 1.413T10 13H8v2h4v2zm7 0l3-5l-3-5h2l2 3.325L19 7h2l-3 5l3 5h-2l-2-3.325L15 17z");
}

</style>
