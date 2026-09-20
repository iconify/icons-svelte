<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t23ow0bwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-up" {...props}></Icon>
<style>
:global(.t23ow0bwt) {
  fill: currentColor;
  d: path("M6 21q-.825 0-1.412-.587T4 19v-4h16v4q0 .825-.587 1.413T18 21zm-4-8v-2h2V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v6h2v2z");
}

</style>
