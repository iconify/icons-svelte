<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lr8as2bsj"/><path class="zxvreoboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:smartflasher" {...props}></Icon>
<style>
:global(.lr8as2bsj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.66 4.5V24h-6.33l11.01 19.5V24h6.33z");
}

:global(.zxvreoboa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.34 36.55a12.76 12.76 0 0 0-.83-25.22m-3.85.12a12.76 12.76 0 0 0 .83 25.22");
}

</style>
