<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgfryb3wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sticky-note" {...props}></Icon>
<style>
:global(.tgfryb3wm) {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v11l-5 5zm6-5h2v-6h3V8H8v2h3zm4 3l4-4h-2q-.825 0-1.412.588T15 17z");
}

</style>
