<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hyp6v68rm"/><path class="gk4de-b1j"/><path class="v2mer508z"/><path class="ra0ia6tpa"/><path class="ko52u6bwb"/><path class="l10is9spu"/><path class="wwozeg7ww"/><path class="yih0nfb7c"/><path class="qxhe48bjs"/><path class="evq885uwk"/><path class="af7iv3n-p"/><path class="x3jkjl77t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:umbrella-open-duotone-bold" {...props}></Icon>
<style>
:global(.af7iv3n-p) {
  d: path("M12 2v2.5");
}

:global(.evq885uwk) {
  d: path("m5 3 2 2");
}

:global(.gk4de-b1j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hyp6v68rm) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ko52u6bwb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l10is9spu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m19 3 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qxhe48bjs) {
  d: path("M12 14v7");
}

:global(.ra0ia6tpa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 3 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v2mer508z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 14v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wwozeg7ww) {
  d: path("M3 14a9 9 0 0 1 18 0");
}

:global(.x3jkjl77t) {
  d: path("m19 3 -2 2");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>
