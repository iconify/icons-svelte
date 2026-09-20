<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5o82kbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:square" {...props}></Icon>
<style>
:global(.a5o82kbby) {
  fill: currentColor;
  d: path("M4 20V4h16v16z");
}

</style>
