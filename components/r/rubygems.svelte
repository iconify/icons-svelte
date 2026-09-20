<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":293};
const content = `<g class="i160q39rf"><path class="jhull5b7o"/><path class="dgr__5rtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:rubygems" {...props}></Icon>
<style>
:global(.dgr__5rtu) {
  d: path("M127.823.976L.135 74.173v146.395l127.688 73.197l127.689-73.197V74.173zm103.29 205.603l-103.29 59.534l-103.29-59.534V87.837l103.29-59.534l103.29 59.534z");
}

:global(.i160q39rf) {
  fill: var(--svg-color--d34231, #d34231);
}

:global(.jhull5b7o) {
  d: path("m76.748 97.434l-.163-.163l-36.11 36.11l87.674 87.512l36.11-35.948l51.564-51.563l-36.11-36.11v-.164H76.584z");
}

</style>
