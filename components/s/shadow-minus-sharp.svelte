<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khnqc1b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shadow-minus-sharp" {...props}></Icon>
<style>
:global(.khnqc1b-j) {
  fill: currentColor;
  d: path("M2 22V6h4V2h16v16h-4v4zm6-6h12V4H8zm2-5V9h8v2z");
}

</style>
