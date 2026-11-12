<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wqrvqvscl"/><path class="zzt-smbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stepper-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.wqrvqvscl) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a4 4 0 0 1 4-4h12a4 4 0 0 1 4 4v2a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4Z");
}

:global(.zzt-smbzn) {
  d: path("M17 6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm0 15v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0m-8-2H3a1 1 0 0 1 0-2h6a1 1 0 0 1 0 2");
}

</style>
