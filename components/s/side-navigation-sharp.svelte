<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f24-01b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:side-navigation-sharp" {...props}></Icon>
<style>
:global(.f24-01b9t) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm9-2h7V5h-7z");
}

</style>
