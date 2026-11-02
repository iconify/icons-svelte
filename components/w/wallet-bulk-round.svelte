<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l3h0twbhh"/><path class="ihtwd5bzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wallet-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ihtwd5bzq) {
  d: path("M21 10h-3a2 2 0 1 0 0 4h3a1 1 0 0 1 0 2h-3a4 4 0 0 1 0-8h3a1 1 0 0 1 0 2m-3 1h.01a1 1 0 0 1 0 2H18a1 1 0 0 1 0-2");
}

:global(.l3h0twbhh) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5Z");
}

</style>
