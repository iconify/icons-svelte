<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tw7y6mbhw"/><path class="gi76mbcrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:volume-minus-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gi76mbcrc) {
  d: path("M15 11h6a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2");
}

:global(.tw7y6mbhw) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4v16a1.002 1.002 0 0 1-1.707.707L6.586 17H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 12 4");
}

</style>
