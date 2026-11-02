<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qjltbu0ug"/><path class="scc1kvjkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-off-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.qjltbu0ug) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.828 15.586L8.414 7.172l4.879-4.879A1 1 0 0 1 15 3v7h5a1.002 1.002 0 0 1 .707 1.707ZM14 17l.707.707l-4 4A1 1 0 0 1 9 21v-7H4a1.002 1.002 0 0 1-.707-1.707l3-3Z");
}

:global(.scc1kvjkf) {
  d: path("m2.707 4.293l17 17a.999.999 0 1 1-1.414 1.414l-17-17a.999.999 0 1 1 1.414-1.414");
}

</style>
