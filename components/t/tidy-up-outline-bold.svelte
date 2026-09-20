<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lhk-ji-wo"/><path class="lh_8lcb-x"/><path class="icvc39peu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tidy-up-outline-bold" {...props}></Icon>
<style>
:global(.icvc39peu) {
  d: path("m9 7 3 3 3 -3");
}

:global(.lh_8lcb-x) {
  d: path("M12 4v6");
}

:global(.lhk-ji-wo) {
  d: path("M5 12v8h14v-8Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
