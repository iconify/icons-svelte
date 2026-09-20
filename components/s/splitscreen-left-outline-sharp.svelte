<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxq4918bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:splitscreen-left-outline-sharp" {...props}></Icon>
<style>
:global(.xxq4918bf) {
  fill: currentColor;
  d: path("M3 21V3h8v18zm10 0V3h8v18zm6-16h-4v14h4z");
}

</style>
