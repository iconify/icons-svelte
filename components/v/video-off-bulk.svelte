<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gth1w_bgj"/><path class="popaz21gp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:video-off-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gth1w_bgj) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.218 17.976L8.243 5H13a3 3 0 0 1 3 3v.382l2.553-1.276c.356-.181.75-.274 1.149-.273C20.924 6.836 22 7.735 22 9v8a1 1 0 0 1-.782.976m-5.346-1.104A3.005 3.005 0 0 1 13 19H5a3 3 0 0 1-3-3V8c0-1.32.866-2.487 2.128-2.872Z");
}

:global(.popaz21gp) {
  d: path("M1.293 3.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
