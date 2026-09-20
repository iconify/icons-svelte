<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ewcibzbps"/><path class="qxhe48bjs"/><path class="ulbp0sbur"/><path class="hvp96bbhp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:treehouse-outline-bold" {...props}></Icon>
<style>
:global(.ewcibzbps) {
  d: path("M5 14V9l7 -7 7 7v5Z");
}

:global(.hvp96bbhp) {
  d: path("m12 18 4 -4");
}

:global(.qxhe48bjs) {
  d: path("M12 14v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ulbp0sbur) {
  d: path("m12 18 -4 -4");
}

</style>
