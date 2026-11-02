<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nkq2_lbze"/><path class="fwp9lvbrl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-forward-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fwp9lvbrl) {
  d: path("M21 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

:global(.nkq2_lbze) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m7.59 4.456l8 5a3 3 0 0 1 0 5.088l-8 5A2.999 2.999 0 0 1 3 17V7a3 3 0 0 1 4.59-2.544");
}

</style>
