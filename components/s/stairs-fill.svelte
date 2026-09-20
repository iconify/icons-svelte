<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y0e08nbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:stairs-fill" {...props}></Icon>
<style>
:global(.y0e08nbnx) {
  fill: currentColor;
  d: path("M200 24H56a16 16 0 0 0-16 16v176a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V40a16 16 0 0 0-16-16m-40 80h40v24h-40Zm-48 40h88v24h-88Zm88 72H56v-32h144z");
}

</style>
