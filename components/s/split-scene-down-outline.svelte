<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etvlcqq-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:split-scene-down-outline" {...props}></Icon>
<style>
:global(.etvlcqq-d) {
  fill: currentColor;
  d: path("M4 9V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v4h-2V5H6v4zm2 12q-.825 0-1.412-.587T4 19v-6H2v-2h20v2h-2v6q0 .825-.587 1.413T18 21zM6 5h12z");
}

</style>
