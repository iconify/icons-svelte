<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au42eccqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:splitscreen-landscape-add-sharp" {...props}></Icon>
<style>
:global(.au42eccqb) {
  fill: currentColor;
  d: path("M19 8V6h-2V4h2V2h2v2h2v2h-2v2zM6 16h5V8H6zm-4 4V4h13.1q-.05.25-.075.5T15 5q0 .85.263 1.613T16 8h-3v8h5V9.575q.45.2.963.313T20 10t1.025-.112t.975-.313V20z");
}

</style>
