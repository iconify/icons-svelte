<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kw2csablp"/><path class="ukhmdccjx"/><path class="dhme87bwo"/><path class="z_2cvsa8b"/><path class="zaau21ski"/><path class="vj8si9dha"/><path class="fa2e7y2tg"/><path class="wfg0vmbgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:syntax-duotone-regular" {...props}></Icon>
<style>
:global(.dhme87bwo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 17h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.fa2e7y2tg) {
  d: path("M4 17h8");
}

:global(.kw2csablp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4 4 8l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ukhmdccjx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 4 4 4 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vj8si9dha) {
  d: path("m16 4 4 4 -4 4");
}

:global(.wfg0vmbgy) {
  d: path("M15 17h5");
}

:global(.z_2cvsa8b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zaau21ski) {
  d: path("M8 4 4 8l4 4");
}

</style>
