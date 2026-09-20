<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jqc-dlrxf"/><path class="rw6ho_bav"/><path class="r_je2bdjk"/><path class="koh8ckbdb"/><path class="k2mg4f2ls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:school-bus-outline-regular" {...props}></Icon>
<style>
:global(.jqc-dlrxf) {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.k2mg4f2ls) {
  d: path("M15 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.koh8ckbdb) {
  d: path("M5 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r_je2bdjk) {
  d: path("M12 4v5");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

</style>
