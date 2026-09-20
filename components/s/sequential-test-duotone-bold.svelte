<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j3vc2bk9z"/><path class="hegns5bav"/><path class="am9g3fbhn"/><path class="h5r2q9lol"/><path class="s98e5-qqv"/><path class="iaj8d8bgd"/><path class="w_4k9q5tv"/><path class="m__qgi9_a"/><path class="nhzanrbsp"/><path class="r8i1ojbwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sequential-test-duotone-bold" {...props}></Icon>
<style>
:global(.am9g3fbhn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17.5 7 3.5 3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h5r2q9lol) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m21 7 -3.5 3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hegns5bav) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 8 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iaj8d8bgd) {
  d: path("m3 8 2 2 3 -3");
}

:global(.j3vc2bk9z) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 8 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m__qgi9_a) {
  d: path("m17.5 7 3.5 3.5");
}

:global(.nhzanrbsp) {
  d: path("m21 7 -3.5 3.5");
}

:global(.r8i1ojbwn) {
  d: path("M3 16.5h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s98e5-qqv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16.5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w_4k9q5tv) {
  d: path("m10 8 2 2 3 -3");
}

</style>
