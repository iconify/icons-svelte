<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="varxkfibx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:stop-button" {...props}></Icon>
<style>
:global(.varxkfibx) {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32c0 16.569 13.432 30 30 30s30-13.431 30-30C62 15.432 48.568 2 32 2m15 45H17V17h30z");
}

</style>
