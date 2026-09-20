<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ded97twic"/><path class="o_lgmdh9h"/><path class="bpco9rrox"/><path class="mnswn9nsk"/><path class="wjqx41ynh"/><path class="kamdbib6v"/><path class="pmuiqo95v"/><path class="kt4_ogrrr"/><path class="hgjyjobhk"/><path class="gvpticbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:waist-measure-duotone-bold" {...props}></Icon>
<style>
:global(.bpco9rrox) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ded97twic) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gvpticbjc) {
  d: path("M18 7v4");
}

:global(.hgjyjobhk) {
  d: path("M12 7v4");
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.kt4_ogrrr) {
  d: path("M6 7v4");
}

:global(.mnswn9nsk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o_lgmdh9h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wjqx41ynh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
