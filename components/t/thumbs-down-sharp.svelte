<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b8xyz8pvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:thumbs-down-sharp" {...props}></Icon>
<style>
:global(.b8xyz8pvp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.25 13.75l3.5 6.5a2 2 0 0 0 3-2.2l-.9-3.55h4.65l2.75-.006l-.55-2.694l-1.4-6.5l-.367-1.796L17.1 3.5H8.25ZM2.75 3.5h3v10.25h-3z");
}

</style>
