<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afs69qbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sensor-window-outline-sharp" {...props}></Icon>
<style>
:global(.afs69qbhv) {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-11h4v-1h4v1h4V4H6zm0 2v7h12v-7zm0 7h12z");
}

</style>
