<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r2iy4tbeq"/><path class="vy7jk_b7v"/><path class="yd5tqobrd"/><path class="e7df_8bvz"/><path class="yeuzzbchl"/><path class="coi-np7dk"/><path class="vckqcjbbb"/><path class="pst98pbad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:voice-agent-duotone-regular" {...props}></Icon>
<style>
:global(.coi-np7dk) {
  d: path("M15 9v6");
}

:global(.e7df_8bvz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pst98pbad) {
  d: path("M21 10v4");
}

:global(.r2iy4tbeq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.11 7.47a5 5 0 1 1 -4.22 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vckqcjbbb) {
  d: path("M18 5v14");
}

:global(.vy7jk_b7v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yd5tqobrd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yeuzzbchl) {
  d: path("M9.11 7.47a5 5 0 1 1 -4.22 0");
}

</style>
