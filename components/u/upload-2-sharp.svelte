<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yottlqj1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:upload-2-sharp" {...props}></Icon>
<style>
:global(.yottlqj1f) {
  fill: currentColor;
  d: path("M5 21v-1h14v1zm4.635-3.77v-6.788h-3.27L12 3l5.616 7.442h-3.27v6.789z");
}

</style>
