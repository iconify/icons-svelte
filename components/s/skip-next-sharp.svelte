<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnzfptejd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:skip-next-sharp" {...props}></Icon>
<style>
:global(.tnzfptejd) {
  fill: currentColor;
  d: path("M16.27 16.616V7.385h1v9.23zm-9.54 0V7.385L13.655 12z");
}

</style>
