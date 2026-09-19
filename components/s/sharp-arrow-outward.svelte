<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4dnnzrwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-arrow-outward" {...props}></Icon>
<style>
:global(.n4dnnzrwg) {
  fill: currentColor;
  d: path("M6 6v2h8.59L5 17.59L6.41 19L16 9.41V18h2V6z");
}

</style>
