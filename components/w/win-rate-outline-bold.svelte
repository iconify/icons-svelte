<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o_ssmh9ez"/><path class="j8_8pdbyc"/><path class="zrdou8b0n"/><path class="w9oq4pbyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:win-rate-outline-bold" {...props}></Icon>
<style>
:global(.j8_8pdbyc) {
  d: path("M12 3v9");
}

:global(.o_ssmh9ez) {
  d: path("M3 12a9 9 0 1 0 18 0 9 9 0 1 0 -18 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w9oq4pbyv) {
  d: path("m5 14 2 2 3.5 -3.5");
}

:global(.zrdou8b0n) {
  d: path("M12 12h9");
}

</style>
