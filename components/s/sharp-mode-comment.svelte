<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce56lbbkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-mode-comment" {...props}></Icon>
<style>
:global(.ce56lbbkn) {
  fill: currentColor;
  d: path("M22 2H2v16h16l4 4z");
}

</style>
