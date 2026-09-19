<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fsewhnb2e"/><path class="oizle1nqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:sadapay" {...props}></Icon>
<style>
:global(.fsewhnb2e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.392 44.559L9.525 30.692m13.4-27.133l13.867 13.868m-21.588 8.22l7.624-7.625c4.02-4.02 10.313-4.245 14.055-.503h0c3.743 3.742 3.518 10.035-.503 14.055l-7.666 7.667");
}

:global(.oizle1nqu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.113 22.472l-7.624 7.625c-4.02 4.02-10.313 4.245-14.055.503h0c-3.743-3.742-3.518-10.035.503-14.055l7.666-7.667");
}

</style>
