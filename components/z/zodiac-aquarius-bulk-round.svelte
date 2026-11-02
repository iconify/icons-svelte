<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uswdmbucs"/><path class="ke3ciypru"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-aquarius-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ke3ciypru) {
  d: path("M4.293 7.293a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-2 2a.999.999 0 1 1-1.414-1.414Z");
}

:global(.uswdmbucs) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.293 14.293a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l1 1a.414.414 0 0 0 .586 0l1-1a2.414 2.414 0 0 1 3.414 0l2 2a.999.999 0 1 1-1.414 1.414l-2-2a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-1 1a2.414 2.414 0 0 1-3.414 0l-1-1a.414.414 0 0 0-.586 0l-2 2a.999.999 0 1 1-1.414-1.414Z");
}

</style>
