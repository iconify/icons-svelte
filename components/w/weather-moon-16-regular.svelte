<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uakppg9hq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:weather-moon-16-regular" {...props}></Icon>
<style>
:global(.uakppg9hq) {
  fill: currentColor;
  d: path("M8.003 1a7 7 0 1 1-6.465 9.691a.5.5 0 0 1 .474-.692A6 6 0 0 0 7.54 1.692A.5.5 0 0 1 8.003 1m.719 1.044a7 7 0 0 1-5.941 8.911a6 6 0 1 0 5.941-8.911");
}

</style>
