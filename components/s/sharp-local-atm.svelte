<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scvxqdbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-local-atm" {...props}></Icon>
<style>
:global(.scvxqdbhp) {
  fill: currentColor;
  d: path("M11 17h2v-1h2v-5h-4v-1h4V8h-2V7h-2v1H9v5h4v1H9v2h2zM22 4H2.01L2 20h20zm-2 14H4V6h16z");
}

</style>
