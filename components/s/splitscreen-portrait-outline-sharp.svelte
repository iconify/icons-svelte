<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahtp96bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:splitscreen-portrait-outline-sharp" {...props}></Icon>
<style>
:global(.ahtp96bhg) {
  fill: currentColor;
  d: path("M8.385 17.616h7.23v-4.424h-7.23zm0-6.808h7.23V6.385h-7.23zM5 21V3h14v18zm1-1h12V4H6zM18 4H6z");
}

</style>
