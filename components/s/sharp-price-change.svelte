<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pumg_ybch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-price-change" {...props}></Icon>
<style>
:global(.pumg_ybch) {
  fill: currentColor;
  d: path("M2 4v16h20V4zm10 6H8v1h4v5h-2v1H8v-1H6v-2h4v-1H6V8h2V7h2v1h2zm4 6.25l-2-2h4zM14 10l2-2l2 2z");
}

</style>
