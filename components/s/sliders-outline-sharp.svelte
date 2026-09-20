<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yit-lcg9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sliders-outline-sharp" {...props}></Icon>
<style>
:global(.yit-lcg9h) {
  fill: currentColor;
  d: path("M2 15V9h20v6zm12-2h6v-2h-6z");
}

</style>
