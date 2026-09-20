<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qetmcvbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-real-size-sharp" {...props}></Icon>
<style>
:global(.qetmcvbut) {
  fill: currentColor;
  d: path("M7.827 16V9H6V8h2.827v8zm3.635 0v-1h1v1zM16 16V9h-1.808V8H17v8zm-4.538-3.5v-1h1v1z");
}

</style>
