<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py0fbwqdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:subject" {...props}></Icon>
<style>
:global(.py0fbwqdu) {
  fill: currentColor;
  d: path("M14 17H4v2h10zm6-8H4v2h16zM4 15h16v-2H4zM4 5v2h16V5z");
}

</style>
