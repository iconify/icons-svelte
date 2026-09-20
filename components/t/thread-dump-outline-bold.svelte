<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n0n63pb2v"/><path class="v_bddgbtn"/><path class="ly7sc7y4x"/><path class="pp_20ub-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:thread-dump-outline-bold" {...props}></Icon>
<style>
:global(.ly7sc7y4x) {
  d: path("M12 5v7");
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.pp_20ub-w) {
  d: path("M16 5v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v_bddgbtn) {
  d: path("M8 5v7");
}

</style>
