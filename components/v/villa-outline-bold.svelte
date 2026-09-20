<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mi_rhabsp"/><path class="pm0e7ny3b"/><path class="tbo01n9ke"/><path class="s88iiwf1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:villa-outline-bold" {...props}></Icon>
<style>
:global(.mi_rhabsp) {
  d: path("m2 11 6 -6 6 6");
}

:global(.pm0e7ny3b) {
  d: path("M4 11v8h8v-8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.s88iiwf1g) {
  d: path("m15 19 2 -2 2 2 2 -2");
}

:global(.tbo01n9ke) {
  d: path("m15 14 2 -2 2 2 2 -2");
}

</style>
