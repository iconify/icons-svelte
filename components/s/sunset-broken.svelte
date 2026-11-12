<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lt7j86jjt"/><path class="cz_7jaczd"/><path class="l6md27rub"/><path class="lgwh98i9y"/><path class="lq7a-_8su"/><path class="qi4ad9bta"/><path class="i0kw3he6n"/><path class="de5cici1x"/><path class="ftpy_bcfw"/><path class="imyk_5tkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:sunset-broken" {...props}></Icon>
<style>
:global(.cz_7jaczd) {
  stroke-linejoin: round;
  d: path("M5 19H19");
}

:global(.de5cici1x) {
  d: path("M19.0703 4.9292L18.6775 5.32204");
}

:global(.ftpy_bcfw) {
  d: path("M5.32227 5.32178L4.92943 4.92894");
}

:global(.i0kw3he6n) {
  d: path("M3 12L2 12");
}

:global(.imyk_5tkk) {
  d: path("M10 6.34141C10.6256 6.12031 11.2987 6 12 6C15.3137 6 18 8.68629 18 12C18 13.5217 17.4335 14.911 16.5 15.9687H7.5C6.56645 14.911 6 13.5217 6 12C6 11.2987 6.12031 10.6256 6.34141 10");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l6md27rub) {
  stroke-linejoin: round;
  d: path("M2 16H22");
}

:global(.lgwh98i9y) {
  stroke-linejoin: round;
  d: path("M12 6V13M10 11L12 13L14 11");
}

:global(.lq7a-_8su) {
  d: path("M12 2V3");
}

:global(.lt7j86jjt) {
  stroke-linejoin: round;
  d: path("M8 22H16");
}

:global(.qi4ad9bta) {
  d: path("M22 12L21 12");
}

</style>
