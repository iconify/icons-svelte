<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b15spvb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:table-sharp" {...props}></Icon>
<style>
:global(.b15spvb_j) {
  fill: currentColor;
  d: path("M11.5 14.885H4V20h7.5zm1 0V20H20v-5.115zm-1-1V8.769H4v5.116zm1 0H20V8.769h-7.5zM4 7.769h16V4H4z");
}

</style>
