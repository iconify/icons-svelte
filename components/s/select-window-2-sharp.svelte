<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_dgpuhxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:select-window-2-sharp" {...props}></Icon>
<style>
:global(.w_dgpuhxm) {
  fill: currentColor;
  d: path("M20 14.212V6.846H6.77V3H21v11.212zM3 21V9.23h14.616V21z");
}

</style>
