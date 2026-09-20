<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rvub71bbg"/><path class="d5b4fcc2f"/><path class="o2majduui"/><path class="hy21qfk9p"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="oh3t_sdfd"/><path class="b4nrz0b6r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tab-close-duotone-bold" {...props}></Icon>
<style>
:global(.b4nrz0b6r) {
  d: path("m20.5 10.5 -5 5");
}

:global(.d5b4fcc2f) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hy21qfk9p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m20.5 10.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o2majduui) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15.5 10.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oh3t_sdfd) {
  d: path("m15.5 10.5 5 5");
}

:global(.oscmqi7_r) {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

:global(.rvub71bbg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
