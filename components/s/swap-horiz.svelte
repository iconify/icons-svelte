<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkydyji_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:swap-horiz" {...props}></Icon>
<style>
:global(.vkydyji_p) {
  fill: currentColor;
  d: path("M6.99 11L3 15l3.99 4v-3H14v-2H6.99zM21 9l-3.99-4v3H10v2h7.01v3z");
}

</style>
