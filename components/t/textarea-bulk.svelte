<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="chmvdccpm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:textarea-bulk" {...props}></Icon>
<style>
:global(.chmvdccpm) {
  d: path("M16 5a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm-6 4a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Zm8.293 3.293a.999.999 0 1 1 1.414 1.414l-6 6a.999.999 0 1 1-1.414-1.414Zm0 5a.999.999 0 1 1 1.414 1.414l-1 1a.999.999 0 1 1-1.414-1.414Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.qebz58hxe) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
