<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u5-gj6qse"/><path class="k-awjwr9r"/><path class="tmfei69qh"/><path class="zh6q_cf_u"/><path class="rwge04jxw"/><path class="g7akhoeoj"/><path class="wlp3ibbib"/><path class="qrqk-5btd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wardrobe-sort-duotone-bold" {...props}></Icon>
<style>
:global(.g7akhoeoj) {
  d: path("m6 13 6 -6 6 6");
}

:global(.k-awjwr9r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrqk-5btd) {
  d: path("m9 17 3 3 3 -3");
}

:global(.rwge04jxw) {
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tmfei69qh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u5-gj6qse) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

:global(.zh6q_cf_u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
