<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tbr--mb3k"/><path class="we4ss1orc"/><path class="ayf_-ac5t"/><path class="lvik9zb3c"/><path class="aun8ln3zw"/><path class="xedmbxbzm"/><path class="t6kwsvo7n"/><path class="pg19afyuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sprinkler-duotone-bold" {...props}></Icon>
<style>
:global(.aun8ln3zw) {
  d: path("M12 12v7");
}

:global(.ayf_-ac5t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8c2 -2 4 -2 6 -1");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lvik9zb3c) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8C7 6 5 6 3 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pg19afyuh) {
  d: path("M9 8C7 6 5 6 3 7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t6kwsvo7n) {
  d: path("M15 8c2 -2 4 -2 6 -1");
}

:global(.tbr--mb3k) {
  fill: currentColor;
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.we4ss1orc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xedmbxbzm) {
  d: path("M10 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
