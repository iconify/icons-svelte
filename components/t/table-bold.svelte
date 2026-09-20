<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pv9a0tbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:table-bold" {...props}></Icon>
<style>
:global(.pv9a0tbfu) {
  fill: currentColor;
  d: path("M224 44H32a12 12 0 0 0-12 12v136a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V56a12 12 0 0 0-12-12M44 116h32v24H44Zm56 0h112v24H100Zm112-48v24H44V68ZM44 164h32v24H44Zm56 24v-24h112v24Z");
}

</style>
