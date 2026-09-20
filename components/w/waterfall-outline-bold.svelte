<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xf07dvr8m"/><path class="tr_jskylo"/><path class="hxoe7gx5p"/><path class="e0001wg8c"/><path class="y_21nobec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:waterfall-outline-bold" {...props}></Icon>
<style>
:global(.e0001wg8c) {
  d: path("M17 5v12");
}

:global(.hxoe7gx5p) {
  d: path("M12 5v12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tr_jskylo) {
  d: path("M7 5v12");
}

:global(.xf07dvr8m) {
  d: path("M2 5h20");
}

:global(.y_21nobec) {
  d: path("m3 21 3 -3 3 3 3 -3 3 3 3 -3 3 3");
}

</style>
