<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydwd7ibnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:xai" {...props}></Icon>
<style>
:global(.ydwd7ibnq) {
  fill: var(--svg-color--ff253a, #ff253a);
  fill-rule: evenodd;
  d: path("M15.669 16.716H8.332l2.614-4.53L9.17 9.11L3 19.794h18L12 4.206l-1.777 3.078z");
}

</style>
