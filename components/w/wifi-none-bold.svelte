<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bne1r35vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wifi-none-bold" {...props}></Icon>
<style>
:global(.bne1r35vq) {
  fill: currentColor;
  d: path("M144 204a16 16 0 1 1-16-16a16 16 0 0 1 16 16");
}

</style>
