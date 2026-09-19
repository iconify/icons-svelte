<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yvs5yqzlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:small-orange-diamond" {...props}></Icon>
<style>
:global(.yvs5yqzlt) {
  fill: currentColor;
  d: path("m16 32l15.999-16l16 16l-16 16z");
}

</style>
