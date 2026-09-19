<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="r9scpwboa"/><path class="z7x0mu8oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:white-square-button" {...props}></Icon>
<style>
:global(.r9scpwboa) {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M2 2h60v60H2z");
}

:global(.z7x0mu8oe) {
  fill: var(--svg-color--333, #333);
  d: path("M10 10h44v44H10z");
}

</style>
