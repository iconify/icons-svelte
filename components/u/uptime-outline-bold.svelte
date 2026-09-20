<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k187sabpz"/><path class="yaok4e85l"/><path class="pdgwdvrql"/><path class="o0r0bcbwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:uptime-outline-bold" {...props}></Icon>
<style>
:global(.k187sabpz) {
  d: path("M2 11h20");
}

:global(.o0r0bcbwx) {
  d: path("m16 6 2 2 4 -4");
}

:global(.pdgwdvrql) {
  d: path("M15 17h7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.yaok4e85l) {
  d: path("M2 17h9");
}

</style>
