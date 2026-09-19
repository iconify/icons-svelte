<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lu1px_bac"/><path class="z79lwxbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:white-square-button" {...props}></Icon>
<style>
:global(.lu1px_bac) {
  fill: currentColor;
  d: path("M2 2v60h60V2zm58 58H4V4h56z");
}

:global(.z79lwxbrh) {
  fill: currentColor;
  d: path("M10 10h44v44H10z");
}

</style>
