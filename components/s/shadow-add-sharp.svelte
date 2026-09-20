<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l72h9wr4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:shadow-add-sharp" {...props}></Icon>
<style>
:global(.l72h9wr4c) {
  fill: currentColor;
  d: path("M13.5 13.5v-3h-3v-1h3v-3h1v3h3v1h-3v3zM3 21V7h3.616V3H21v14.385h-4V21zm4.616-4.615H20V4H7.616z");
}

</style>
