<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nrvmg4baa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:white-small-square" {...props}></Icon>
<style>
:global(.nrvmg4baa) {
  fill: currentColor;
  d: path("M46 18v28H18V18zm2-2H16v32h32z");
}

</style>
