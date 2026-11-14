<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1paqob_g"/><path class="u9_i14azq"/><path class="ro5dg0wjp"/><path class="irnup5byk"/><path class="qc1rb6b7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:yen-line-duotone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.irnup5byk) {
  d: path("M9.25 12H14.75");
}

:global(.qc1rb6b7c) {
  d: path("M9.25 14.5H14.75");
}

:global(.ro5dg0wjp) {
  d: path("M12 12V17");
}

:global(.u9_i14azq) {
  d: path("M8.5 7L12 12L15.5 7");
}

:global(.y1paqob_g) {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 6.4772 6.4772 2 12 2C17.5228 2 22 6.4772 22 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
