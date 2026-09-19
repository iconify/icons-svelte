<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="izcioekpx"/><path class="pw9rwcbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tenbitclockwidget" {...props}></Icon>
<style>
:global(.izcioekpx) {
  cx: 24px;
  cy: 26.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.4px;
  ry: 16.6px;
}

:global(.pw9rwcbbd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.1 28.9V17.5M19 4.5h10.1v3.4H19zm15.6 9.6l2.9-2.7l2.1 2.3l-2.9 2.7");
}

</style>
