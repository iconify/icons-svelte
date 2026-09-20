<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pz8cbl-0n"/><path class="g4vcemb4i"/><path class="k3c7sdb4u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sailing-outline-bold" {...props}></Icon>
<style>
:global(.g4vcemb4i) {
  d: path("M15 8v6h6Z");
}

:global(.k3c7sdb4u) {
  d: path("M3 17h18c-1 2 -4 4 -9 4s-8 -2 -9 -4");
}

:global(.pz8cbl-0n) {
  d: path("M12 4v10H2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
