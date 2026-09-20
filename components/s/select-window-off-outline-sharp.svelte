<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwynmfjui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:select-window-off-outline-sharp" {...props}></Icon>
<style>
:global(.hwynmfjui) {
  fill: currentColor;
  d: path("M20.475 23.3L10.175 13H4v7h12v-4.025l2 2V22H2V9h4v-.175L.675 3.5L2.1 2.075l19.8 19.8zM18 15.125l-2-2L11.875 9H18v4h2V6H8.875L6.15 3.275V2H22v13h-4z");
}

</style>
