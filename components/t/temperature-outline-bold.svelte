<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rxj7i8-nj"/><path class="vt7vyubju"/><path class="vymzkpbdz"/><path class="e2aybg2ii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:temperature-outline-bold" {...props}></Icon>
<style>
:global(.e2aybg2ii) {
  d: path("M14.5 12H18");
}

:global(.rxj7i8-nj) {
  d: path("M9 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vt7vyubju) {
  d: path("M12 4v11");
}

:global(.vymzkpbdz) {
  d: path("M14.5 8H18");
}

</style>
