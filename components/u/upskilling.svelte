<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t7ou-wbhi"/><path class="tw2yh5zle"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:upskilling" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t7ou-wbhi) {
  d: path("M2.5 20v-.75a1.5 1.5 0 0 1 1.5-1.5h4.5a1.5 1.5 0 0 0 1.5-1.5v-.75a1.5 1.5 0 0 1 1.5-1.5H20a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5H4A1.5 1.5 0 0 1 2.5 20M15.832 2.809za.6.6 0 0 1 .593-.519h.15a.6.6 0 0 1 .593.519a.91.91 0 0 0 .552.72l.195.08a.91.91 0 0 0 .899-.118a.6.6 0 0 1 .786.052l.107.107a.6.6 0 0 1 .052.786a.91.91 0 0 0-.118.899l.08.195a.91.91 0 0 0 .72.552a.6.6 0 0 1 .519.593v.15a.6.6 0 0 1-.519.593a.91.91 0 0 0-.72.552l-.08.195a.91.91 0 0 0 .118.899a.6.6 0 0 1-.052.786l-.107.107a.6.6 0 0 1-.786.052a.91.91 0 0 0-.899-.118l-.195.08a.91.91 0 0 0-.552.72a.6.6 0 0 1-.593.519h-.15a.6.6 0 0 1-.593-.519a.91.91 0 0 0-.552-.72l-.195-.08a.91.91 0 0 0-.899.118a.6.6 0 0 1-.786-.052l-.107-.107a.6.6 0 0 1-.052-.786a.91.91 0 0 0 .118-.899l-.08-.195a.91.91 0 0 0-.72-.552a.6.6 0 0 1-.519-.593v-.15a.6.6 0 0 1 .519-.593a.91.91 0 0 0 .72-.552l.08-.195a.91.91 0 0 0-.118-.899a.6.6 0 0 1 .052-.786l.107-.107a.6.6 0 0 1 .786-.052a.91.91 0 0 0 .899.118l.195-.08a.91.91 0 0 0 .552-.72");
}

:global(.tw2yh5zle) {
  d: path("M15.75 6.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
