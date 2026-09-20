<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdy3bxb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-alt-1-bar-outline" {...props}></Icon>
<style>
:global(.sdy3bxb_e) {
  fill: currentColor;
  d: path("M5 20v-6h3v6z");
}

</style>
