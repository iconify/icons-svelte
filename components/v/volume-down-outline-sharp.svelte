<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq6sudv-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:volume-down-outline-sharp" {...props}></Icon>
<style>
:global(.rq6sudv-m) {
  fill: currentColor;
  d: path("M5 15V9h4l5-5v16l-5-5zm11 1V7.95q1.125.525 1.813 1.625T18.5 12t-.687 2.4T16 16m-4-7.15L9.85 11H7v2h2.85L12 15.15zM9.5 12");
}

</style>
