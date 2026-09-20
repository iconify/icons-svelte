<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="apwo9exbc"/><path class="s-j14r68l"/><path class="o3r8utdvv"/><path class="v5d2b2g6o"/><path class="rwge04jxw"/><path class="g7akhoeoj"/><path class="wlp3ibbib"/><path class="qrqk-5btd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:wardrobe-sort-duotone-regular" {...props}></Icon>
<style>
:global(.apwo9exbc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g7akhoeoj) {
  d: path("m6 13 6 -6 6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o3r8utdvv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 13h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qrqk-5btd) {
  d: path("m9 17 3 3 3 -3");
}

:global(.rwge04jxw) {
  d: path("M12 4c1.5 0 1.5 2 0 2.5");
}

:global(.s-j14r68l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v5d2b2g6o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wlp3ibbib) {
  d: path("M6 13h12");
}

</style>
