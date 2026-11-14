<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dps9260it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:station-symbol" {...props}></Icon>
<style>
:global(.dps9260it) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.25 4.5q0-2.75 2.75-2.75t2.75 2.75T12 7.25T9.25 4.5m1.75 4q-1.76 0-3.005 1.245T6.75 12.75V18q0 1.76 1.245 3.005T11 22.25h2q1.76 0 3.005-1.245T17.25 18v-5.25q0-1.76-1.245-3.005T13 8.5z");
}

</style>
