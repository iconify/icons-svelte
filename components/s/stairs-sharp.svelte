<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg47xybxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stairs-sharp" {...props}></Icon>
<style>
:global(.kg47xybxc) {
  fill: currentColor;
  d: path("M6 18h4.425v-3.325H13V11.35h2.575V8H18V6h-4.425v3.325H11v3.325H8.425V16H6zm-3 3V3h18v18z");
}

</style>
