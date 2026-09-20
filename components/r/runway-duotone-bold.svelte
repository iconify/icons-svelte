<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="brh9-pbrz"/><path class="ogebn3b0r"/><path class="up66nkpsb"/><path class="cmia02hko"/><path class="i0d2ocjjv"/><path class="oakk4fbrw"/><path class="ifv_d4f9e"/><path class="d1zyr9bfc"/><path class="iyj_k-bwo"/><path class="jnf_2db5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:runway-duotone-bold" {...props}></Icon>
<style>
:global(.brh9-pbrz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cmia02hko) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 11v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d1zyr9bfc) {
  d: path("M12 4v4");
}

:global(.i0d2ocjjv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 18v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ifv_d4f9e) {
  d: path("M17 2v20");
}

:global(.iyj_k-bwo) {
  d: path("M12 11v4");
}

:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.oakk4fbrw) {
  d: path("M7 2v20");
}

:global(.ogebn3b0r) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.up66nkpsb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
