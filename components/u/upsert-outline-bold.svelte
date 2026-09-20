<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yih0nfb7c"/><path class="xyj-l9cjp"/><path class="x_7wq3p0y"/><path class="c51p9nb2t"/><path class="nw0y-0bem"/><path class="vb93covwl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:upsert-outline-bold" {...props}></Icon>
<style>
:global(.c51p9nb2t) {
  d: path("m6 6 3 3 3 -3");
}

:global(.nw0y-0bem) {
  d: path("M17 3v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vb93covwl) {
  d: path("M15 5h4");
}

:global(.x_7wq3p0y) {
  d: path("M9 3v5");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>
