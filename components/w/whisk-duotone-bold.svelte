<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n8sdex8rd"/><path class="k9t278v9q"/><path class="k-lk13sge"/><path class="i7rgmjmzy"/><path class="z_j864liq"/><path class="hx7cfzbbm"/><path class="l6rp-_-ny"/><path class="mww7ccc2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:whisk-duotone-bold" {...props}></Icon>
<style>
:global(.hx7cfzbbm) {
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
}

:global(.i7rgmjmzy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 21c0 -6 -1 -12 -2 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k-lk13sge) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 21c0 -6 1 -12 2 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k9t278v9q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21c0 -6 2 -12 6 -12s6 6 6 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l6rp-_-ny) {
  d: path("M10 21c0 -6 1 -12 2 -12");
}

:global(.mww7ccc2b) {
  d: path("M14 21c0 -6 -1 -12 -2 -12");
}

:global(.n8sdex8rd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 2v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z_j864liq) {
  d: path("M12 2v7");
}

</style>
