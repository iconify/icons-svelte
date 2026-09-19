<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-fht_o0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-drive-file-move" {...props}></Icon>
<style>
:global(.s-fht_o0j) {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zM12 17v-3H8v-2h4V9l4 4z");
}

</style>
