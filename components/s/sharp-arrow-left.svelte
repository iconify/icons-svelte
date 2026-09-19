<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oifwthb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-arrow-left" {...props}></Icon>
<style>
:global(.oifwthb4m) {
  fill: currentColor;
  d: path("m14 7l-5 5l5 5z");
}

</style>
