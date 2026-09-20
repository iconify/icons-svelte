<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gadhekz-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screenshot-monitor-sharp" {...props}></Icon>
<style>
:global(.gadhekz-w) {
  fill: currentColor;
  d: path("M15 16h4v-4h-1.5v2.5H15zM5 10h1.5V7.5H9V6H5zm3 11v-2H2V3h20v16h-6v2z");
}

</style>
