<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zyr0_hpav"/><path class="xuznnacny"/><path class="y4_6s7b5v"/><path class="m1mjigbsi"/><path class="nrzizubal"/><path class="wvgu_dbkt"/><path class="ssc15w5pi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tumble-dryer-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m1mjigbsi) {
  d: path("M4 8h16");
}

:global(.nrzizubal) {
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.ssc15w5pi) {
  d: path("M14 17v-4");
}

:global(.wvgu_dbkt) {
  d: path("m10 17 2 -2 -2 -2");
}

:global(.xuznnacny) {
  fill: currentColor;
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.zyr0_hpav) {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
