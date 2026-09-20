<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="d223d_x9q"/><path class="zrdou8b0n"/><path class="uxy9sxbfx"/><path class="wgmfnvzml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:tokenizer-outline-bold" {...props}></Icon>
<style>
:global(.d223d_x9q) {
  d: path("M3 12h6");
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uxy9sxbfx) {
  d: path("M3 19h10");
}

:global(.wgmfnvzml) {
  d: path("M16 19h5");
}

:global(.zrdou8b0n) {
  d: path("M12 12h9");
}

</style>
