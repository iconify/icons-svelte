<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bg5nmnbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:split-scene-up-sharp" {...props}></Icon>
<style>
:global(.bg5nmnbrk) {
  fill: currentColor;
  d: path("M5 20v-5.115h14V20zm-2-7.5v-1h2V4h14v7.5h2v1z");
}

</style>
