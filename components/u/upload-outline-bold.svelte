<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n0n63pb2v"/><path class="tla8vyn6c"/><path class="xp94cyt6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:upload-outline-bold" {...props}></Icon>
<style>
:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tla8vyn6c) {
  d: path("M12 7v8");
}

:global(.xp94cyt6z) {
  d: path("m8 11 4 -4 4 4");
}

</style>
