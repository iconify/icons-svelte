<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvx4_4bnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tokenizer-sharp" {...props}></Icon>
<style>
:global(.vvx4_4bnt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4.5h18.5M12 8v4.5m-2-2l2 2l2-2M2.75 15h4.5v6h-4.5zm7 0h4.5v6h-4.5zm7 0h4.5v6h-4.5z");
}

</style>
