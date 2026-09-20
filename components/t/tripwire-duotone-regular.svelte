<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p7air0nan"/><path class="e25empizl"/><path class="yjfdg-v8n"/><path class="b203w8buy"/><path class="m05of2bop"/><path class="s-etibjpa"/><path class="cwy6p7vpw"/><path class="urilmibxp"/><path class="c_jwtcbat"/><path class="v7xfanbfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tripwire-duotone-regular" {...props}></Icon>
<style>
:global(.b203w8buy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 13h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c_jwtcbat) {
  d: path("M12 3.5V6");
}

:global(.cwy6p7vpw) {
  d: path("M20 10v10");
}

:global(.e25empizl) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m05of2bop) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3.5V6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p7air0nan) {
  fill: currentColor;
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s-etibjpa) {
  d: path("M4 10v10");
}

:global(.urilmibxp) {
  d: path("M4 13h16");
}

:global(.v7xfanbfw) {
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.yjfdg-v8n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 10v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
