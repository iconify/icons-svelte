<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wf6zu9b6f"/><path class="n7sdxmqqs"/><path class="gq7a04b8r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:variable-outline-bold" {...props}></Icon>
<style>
:global(.gq7a04b8r) {
  d: path("M14 14h5");
}

:global(.n7sdxmqqs) {
  d: path("M14 11h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wf6zu9b6f) {
  d: path("M2 9a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
