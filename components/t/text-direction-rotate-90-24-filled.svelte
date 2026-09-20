<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g7uqczr0s"/><path class="fkbee_d8f"/><path class="qk05vebbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-direction-rotate-90-24-filled" {...props}></Icon>
<style>
:global(.fkbee_d8f) {
  d: path("M8 4a1 1 0 0 0-2 0v13.586l-.293-.293a1 1 0 0 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l2-2a1 1 0 0 0-1.414-1.414L8 17.586V4z");
  fill: currentColor;
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g7uqczr0s) {
  d: path("M20.385 8.673l-9 3.75a1 1 0 1 1-.77-1.846L13 9.584V5.917l-2.385-.994a1 1 0 0 1 .77-1.846l9 3.75a1 1 0 0 1 0 1.846zM15 8.75l2.4-1l-2.4-1v2z");
  fill: currentColor;
}

:global(.qk05vebbr) {
  d: path("M16 13a1 1 0 0 0-1 1v3.586l-.293-.293a1 1 0 0 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l2-2a1 1 0 0 0-1.414-1.414l-.293.293V14a1 1 0 0 0-1-1z");
  fill: currentColor;
}

</style>
