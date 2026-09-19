<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mki5yvb1b"/><path class="faab-lbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-smart-screen" {...props}></Icon>
<style>
:global(.faab-lbtd) {
  fill: currentColor;
  d: path("M12.5 11.25H14v1.5h-1.5zm2.5 0h1.5v1.5H15zm-5 0h1.5v1.5H10zm-2.5 0H9v1.5H7.5z");
}

:global(.mki5yvb1b) {
  fill: currentColor;
  d: path("M1 5v14h22V5zm17 12H6V7h12z");
}

</style>
