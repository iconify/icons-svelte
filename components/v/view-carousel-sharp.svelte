<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrx3upght"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-carousel-sharp" {...props}></Icon>
<style>
:global(.jrx3upght) {
  fill: currentColor;
  d: path("M3 16V8h3.346v8zm4.73 2V6h8.54v12zm9.924-2V8H21v8z");
}

</style>
