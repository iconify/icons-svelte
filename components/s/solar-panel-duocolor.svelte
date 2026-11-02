<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znhcflbhe"/><path class="lzezlv4aq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:solar-panel-duocolor" {...props}></Icon>
<style>
:global(.lzezlv4aq) {
  d: path("M6 5h12l2 8H4Zm6 8v6m-4 0h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.znhcflbhe) {
  stroke-opacity: 0.4;
  d: path("M5 9h14m-9-4l-1 8m5-8l1 8");
}

</style>
