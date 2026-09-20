<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-s4vwbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:shadow-outline-sharp" {...props}></Icon>
<style>
:global(.c-s4vwbss) {
  fill: currentColor;
  d: path("M3 21V7h3.616V3H21v14.385h-4V21zm4.616-4.615H20V4H7.616z");
}

</style>
