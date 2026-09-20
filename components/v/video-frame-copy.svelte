<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_66lbbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:video-frame-copy" {...props}></Icon>
<style>
:global(.q_66lbbwo) {
  fill: currentColor;
  d: path("M3 21q-.825 0-1.412-.587T1 19V7h2v12h16v2zM21 8V5h-3V3h3q.825 0 1.413.588T23 5v3zM5 8V5q0-.825.588-1.412T7 3h3v2H7v3zm13 9v-2h3v-3h2v3q0 .825-.587 1.413T21 17zM7 17q-.825 0-1.412-.587T5 15v-3h2v3h3v2zm5-3l6.225-4L12 6z");
}

</style>
