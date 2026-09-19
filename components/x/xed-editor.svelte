<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jry9djbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:xed-editor" {...props}></Icon>
<style>
:global(.jry9djbqu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.949 6.675L24 17.625L13.051 6.674M24 3.5v41M44.5 24h-41m31.449 17.325L24 30.376L13.051 41.325m28.274-6.376L30.376 24l10.949-10.949M6.675 34.949L17.625 24L6.674 13.051");
}

</style>
