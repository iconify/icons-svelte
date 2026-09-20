<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgygz6bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:space-dashboard-sharp" {...props}></Icon>
<style>
:global(.rgygz6bqe) {
  fill: currentColor;
  d: path("M3 21V3h8v18zm10-11V3h8v7zm8 11h-8v-9h8z");
}

</style>
