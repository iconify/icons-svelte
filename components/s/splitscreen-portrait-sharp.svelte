<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aezlwcckt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:splitscreen-portrait-sharp" {...props}></Icon>
<style>
:global(.aezlwcckt) {
  fill: currentColor;
  d: path("M8 18h8v-5H8zm0-7h8V6H8zM4 22V2h16v20z");
}

</style>
