<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylu1r-6jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:today-sharp" {...props}></Icon>
<style>
:global(.ylu1r-6jy) {
  fill: currentColor;
  d: path("M7.225 15.775Q6.5 15.05 6.5 14t.725-1.775T9 11.5t1.775.725T11.5 14t-.725 1.775T9 16.5t-1.775-.725M3 22V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5z");
}

</style>
