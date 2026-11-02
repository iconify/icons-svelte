<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaw40v7pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ticket-fill" {...props}></Icon>
<style>
:global(.yaw40v7pb) {
  fill: currentColor;
  d: path("M13 19H5a3 3 0 0 1-3-3v-1a1 1 0 0 1 1-1a2 2 0 1 0 0-4a1 1 0 0 1-1-1V8a3 3 0 0 1 3-3h8Zm2 0V5h4a3 3 0 0 1 3 3v1a1 1 0 0 1-1 1a2 2 0 1 0 0 4a1 1 0 0 1 1 1v1a3 3 0 0 1-3 3Z");
}

</style>
