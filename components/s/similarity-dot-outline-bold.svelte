<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b5ic9acln"/><path class="m6r9k7-tj"/><path class="xy8m-mq7h"/><path class="q28cmybwy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:similarity-dot-outline-bold" {...props}></Icon>
<style>
:global(.b5ic9acln) {
  d: path("m15 7 5 5 -8 8 -8 -8 5 -5");
}

:global(.m6r9k7-tj) {
  d: path("M8 14.5h8");
}

:global(.q28cmybwy) {
  d: path("M13.5 10v4.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xy8m-mq7h) {
  d: path("m9 14.5 4.5 -4.5");
}

</style>
