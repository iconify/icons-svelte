<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piufsb68s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-sd-card-alert" {...props}></Icon>
<style>
:global(.piufsb68s) {
  fill: currentColor;
  d: path("M20 2H10L4 8v14h16zm-7 15h-2v-2h2zm0-4h-2V8h2z");
}

</style>
