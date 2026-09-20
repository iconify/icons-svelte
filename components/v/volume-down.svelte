<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0cjqm9eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:volume-down" {...props}></Icon>
<style>
:global(.r0cjqm9eg) {
  fill: currentColor;
  d: path("M5 15V9h4l5-5v16l-5-5zm11 1V7.95q1.125.525 1.813 1.625T18.5 12t-.687 2.4T16 16");
}

</style>
