<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hl2w_eimj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:signal-zero-bold" {...props}></Icon>
<style>
:global(.hl2w_eimj) {
  fill: currentColor;
  d: path("M3 19.25C3.41421 19.25 3.75 19.5858 3.75 20C3.75 20.4142 3.41421 20.75 3 20.75C2.58579 20.75 2.25 20.4142 2.25 20C2.25 19.5858 2.58579 19.25 3 19.25Z");
}

</style>
