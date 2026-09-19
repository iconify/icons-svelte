<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="dxs3_thzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:white-small-square" {...props}></Icon>
<style>
:global(.dxs3_thzc) {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M16 16h32v32H16z");
}

</style>
