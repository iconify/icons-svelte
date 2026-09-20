<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ihz07iknx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-description-16-filled" {...props}></Icon>
<style>
:global(.ihz07iknx) {
  fill: currentColor;
  d: path("M1.75 3a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5zM1 9.75A.75.75 0 0 1 1.75 9h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 9.75M1.75 12a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
}

</style>
