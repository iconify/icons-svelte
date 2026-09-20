<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kb8t6m4sf"/><path class="t7ig_mg-l"/><path class="v9wjrcboq"/><path class="iy612dbwv"/><path class="iiqs2_7xi"/><path class="ohhz_s35v"/><path class="kzxwn_jgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:till-count-duotone-bold" {...props}></Icon>
<style>
:global(.iiqs2_7xi) {
  d: path("M9 12v6");
}

:global(.iy612dbwv) {
  d: path("M18 4v4");
}

:global(.kb8t6m4sf) {
  fill: currentColor;
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.kzxwn_jgc) {
  d: path("M15 12v6");
}

:global(.ohhz_s35v) {
  d: path("M12 12v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t7ig_mg-l) {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.v9wjrcboq) {
  d: path("M4 8V3h10v5");
}

</style>
