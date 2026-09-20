<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujic83bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tv-sharp" {...props}></Icon>
<style>
:global(.ujic83bgb) {
  fill: currentColor;
  d: path("M8 21v-2H2V3h20v16h-6v2z");
}

</style>
