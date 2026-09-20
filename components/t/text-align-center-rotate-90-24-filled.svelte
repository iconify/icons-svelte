<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6q_jlbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-center-rotate-90-24-filled" {...props}></Icon>
<style>
:global(.r6q_jlbkm) {
  fill: currentColor;
  d: path("M18 4a1 1 0 0 1 1 1v14a1 1 0 1 1-2 0V5a1 1 0 0 1 1-1M6 6a1 1 0 0 1 1 1v10a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1m7-3a1 1 0 1 0-2 0v18a1 1 0 1 0 2 0z");
}

</style>
