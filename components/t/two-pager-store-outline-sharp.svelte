<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ib4nbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:two-pager-store-outline-sharp" {...props}></Icon>
<style>
:global(.l7ib4nbxj) {
  fill: currentColor;
  d: path("M2 20V4h20v7h-2V6h-7v5h-2V6H4v12h7v2zm12 2v-4.25h2V20h4v-2.25h2V22zm-1.2-4l1-5h8.4l1 5zm2.425-2h5.55l-.2-1h-5.15zM5 16h5v-2H5zm0-3h5v-2H5zm0-3h5V8H5zm9 0V8h5v2zM4 18V6z");
}

</style>
