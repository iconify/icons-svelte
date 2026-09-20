<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cnjf-ebwx"/><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="v63bpsg0s"/><path class="g-xhh1mor"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="b6gnpqbjb"/><path class="nzb-j6sxx"/><path class="rnyye8dag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:secret-block-duotone-bold" {...props}></Icon>
<style>
:global(.b6gnpqbjb) {
  d: path("M10 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.c1kziyotx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cnjf-ebwx) {
  fill: currentColor;
  d: path("M10 10.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.d6cu3qpew) {
  d: path("M17 3h4v18h-4");
}

:global(.g-xhh1mor) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 13.5h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hieqhxiaw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldodvk1_f) {
  d: path("M7 3H3v18h4");
}

:global(.nzb-j6sxx) {
  d: path("M12 12.5V15");
}

:global(.rnyye8dag) {
  d: path("M12 13.5h2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v63bpsg0s) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 12.5V15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
