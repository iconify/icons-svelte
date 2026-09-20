<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="pty_wsbvs"/><path class="gcalxb98a"/><path class="qtxvlht3c"/><path class="ozrmsubaj"/><path class="r2fb1fafl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sentence-window-outline-bold" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.gcalxb98a) {
  d: path("M8 13h8");
}

:global(.ozrmsubaj) {
  d: path("M9.5 11v4");
}

:global(.pty_wsbvs) {
  d: path("M8 9h8");
}

:global(.qtxvlht3c) {
  d: path("M8 17h8");
}

:global(.r2fb1fafl) {
  d: path("M14.5 11v4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
