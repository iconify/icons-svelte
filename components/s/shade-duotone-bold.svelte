<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="teqd5v2_o"/><path class="g55pkgb9q"/><path class="b5u3iabvd"/><path class="p04ylgbfu"/><path class="ckawxab4i"/><path class="d8abqfbpc"/><path class="rdv9wsbxa"/><path class="u78lc2bnx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:shade-duotone-bold" {...props}></Icon>
<style>
:global(.b5u3iabvd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ckawxab4i) {
  d: path("m4 11 8 -8 8 8");
}

:global(.d8abqfbpc) {
  d: path("M3 11h18");
}

:global(.g55pkgb9q) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p04ylgbfu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 20h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rdv9wsbxa) {
  d: path("M12 11v9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.teqd5v2_o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 11 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u78lc2bnx) {
  d: path("M6 20h12");
}

</style>
