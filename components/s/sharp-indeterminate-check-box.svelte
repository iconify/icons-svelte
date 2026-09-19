<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrey22syf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-indeterminate-check-box" {...props}></Icon>
<style>
:global(.lrey22syf) {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-4 10H7v-2h10z");
}

</style>
