<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="d_r8oxwkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-density-28-filled" {...props}></Icon>
<style>
:global(.d_r8oxwkq) {
  fill: currentColor;
  d: path("M14.25 2a.75.75 0 0 1 .75.75v22.5a.75.75 0 0 1-1.5 0V2.75a.75.75 0 0 1 .75-.75M12 5H4a.75.75 0 0 0 0 1.5h8zm0 4H4a.75.75 0 0 0 0 1.5h8zm0 4H4a.75.75 0 0 0 0 1.5h8zm0 4H4a.75.75 0 0 0 0 1.5h8zm0 4H4a.75.75 0 0 0 0 1.5h8zm10.5 0h-6v-5h6a2.5 2.5 0 0 1 0 5m0-9h-6V7h6a2.5 2.5 0 0 1 0 5");
}

</style>
