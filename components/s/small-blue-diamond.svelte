<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="od2kd3bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-v1:small-blue-diamond" {...props}></Icon>
<style>
:global(.od2kd3bdj) {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M32.507 56.655L8.136 32.667L32.507 8.678l24.366 23.989z");
}

</style>
