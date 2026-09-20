<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b76o_ic9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-underline-character-u-24-regular" {...props}></Icon>
<style>
:global(.b76o_ic9k) {
  fill: currentColor;
  d: path("M8.5 4.75a.75.75 0 0 0-1.5 0V12a5 5 0 0 0 10 0V4.75a.75.75 0 0 0-1.5 0V12a3.5 3.5 0 1 1-7 0zM6.75 18.5a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5z");
}

</style>
