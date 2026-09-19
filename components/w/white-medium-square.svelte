<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ueq0-m88d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:white-medium-square" {...props}></Icon>
<style>
:global(.ueq0-m88d) {
  fill: currentColor;
  d: path("M54 10v44H10V10zm2-2H8v48h48z");
}

</style>
