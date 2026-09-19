<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it8s0_guq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-stay-current-landscape" {...props}></Icon>
<style>
:global(.it8s0_guq) {
  fill: currentColor;
  d: path("M1 19h22V5H1zM19 7v10H5V7z");
}

</style>
