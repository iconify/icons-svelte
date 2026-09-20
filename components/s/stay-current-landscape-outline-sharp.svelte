<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccg76on8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stay-current-landscape-outline-sharp" {...props}></Icon>
<style>
:global(.ccg76on8h) {
  fill: currentColor;
  d: path("M2 18V6h20v12zm2.5-1V7H3v10zm1 0h13V7h-13zm14 0H21V7h-1.5zM4.5 7H3zm15 0H21z");
}

</style>
