<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y14yqobtv"/><path class="peqb83hry"/><path class="v6p_b6bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-unfold-less-double" {...props}></Icon>
<style>
:global(.peqb83hry) {
  fill: currentColor;
  d: path("M16.58 6.41L15.16 5l-3.17 3.17L8.82 5L7.41 6.41L11.99 11zM7.42 17.59L8.84 19l3.17-3.17L15.18 19l1.41-1.41L12.01 13z");
}

:global(.v6p_b6bev) {
  fill: currentColor;
  d: path("M7.42 22.59L8.84 24l3.17-3.17L15.18 24l1.41-1.41L12.01 18z");
}

:global(.y14yqobtv) {
  fill: currentColor;
  d: path("M16.58 1.41L15.16 0l-3.17 3.17L8.82 0L7.41 1.41L11.99 6z");
}

</style>
