<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag8vmcb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:toggle-left-fill-round" {...props}></Icon>
<style>
:global(.ag8vmcb-e) {
  fill: currentColor;
  d: path("M9 5h6a7 7 0 1 1 0 14H9A7 7 0 1 1 9 5m-3.685 5.443a4 4 0 1 0 7.37 3.114a4 4 0 0 0-7.37-3.114");
}

</style>
