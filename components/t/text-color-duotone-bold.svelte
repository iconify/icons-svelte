<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nxwhdxb_j"/><path class="fvuj57bsa"/><path class="nu737tjew"/><path class="sqsxh9blm"/><path class="tklpoac2f"/><path class="ui32hib9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:text-color-duotone-bold" {...props}></Icon>
<style>
:global(.fvuj57bsa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 5v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nu737tjew) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 20h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nxwhdxb_j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 5h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sqsxh9blm) {
  d: path("M5 5h14");
}

:global(.tklpoac2f) {
  d: path("M12 5v10");
}

:global(.ui32hib9b) {
  d: path("M5 20h14");
}

</style>
