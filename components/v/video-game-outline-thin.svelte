<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mprhlt90i"/><path class="yb9iu4bmw"/><path class="ffs26fbkv"/><path class="wneoubc6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:video-game-outline-thin" {...props}></Icon>
<style>
:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mprhlt90i) {
  d: path("M3 4v13h18V4Z");
}

:global(.wneoubc6n) {
  d: path("M7 21h10");
}

:global(.yb9iu4bmw) {
  d: path("M9 8h6v5H9Z");
}

</style>
