<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xafv9k1ml"/><path class="j8uz70oyg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:watch-location" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j8uz70oyg) {
  d: path("m8.75 6.25l.5-3.5h5.5l.5 3.5m-6.5 11.5l.5 3.5h5.5l.5-3.5M12 9.25V12l1.75 1.25");
}

:global(.xafv9k1ml) {
  width: 12.5px;
  height: 11.5px;
  x: 5.75px;
  y: 6.25px;
  rx: 3px;
}

</style>
