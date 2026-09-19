<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alpgeibpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-work-outline" {...props}></Icon>
<style>
:global(.alpgeibpq) {
  fill: currentColor;
  d: path("M14 6V4h-4v2zM4 8v11h16V8zm18-2v15H2.01V6H8V4c0-1.1.9-2 2-2h4c1.1 0 2 .9 2 2v2z");
}

</style>
