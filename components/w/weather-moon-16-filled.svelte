<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l34a03bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:weather-moon-16-filled" {...props}></Icon>
<style>
:global(.l34a03bys) {
  fill: currentColor;
  d: path("M8.003 1a7 7 0 1 1-6.465 9.691a.5.5 0 0 1 .474-.692A6 6 0 0 0 7.54 1.692A.5.5 0 0 1 8.003 1");
}

</style>
