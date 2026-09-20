<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isv6rdb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-distributed-vertical-24-filled" {...props}></Icon>
<style>
:global(.isv6rdb8o) {
  fill: currentColor;
  d: path("M19 5.414V21a1 1 0 1 1-2 0V5.414l-.293.293a1 1 0 1 1-1.414-1.414l2-2a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1-1.414 1.414zM5 18.586l-.293-.293a1 1 0 0 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l2-2a1 1 0 1 0-1.414-1.414L7 18.586V3a1 1 0 1 0-2 0zM13 3a1 1 0 1 0-2 0v18a1 1 0 1 0 2 0z");
}

</style>
