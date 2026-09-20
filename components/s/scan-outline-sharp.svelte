<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgisxui8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:scan-outline-sharp" {...props}></Icon>
<style>
:global(.mgisxui8f) {
  fill: currentColor;
  d: path("M5 21v-4.5h1V20h12v-3.5h1V21zm0-9.5V3h9.5L19 7.5v4h-1V8h-4V4H6v7.5zm-3.423 3v-1h20.846v1zM12 16.5");
}

</style>
