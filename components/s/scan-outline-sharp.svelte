<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx3apj_1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:scan-outline-sharp" {...props}></Icon>
<style>
:global(.qx3apj_1v) {
  fill: currentColor;
  d: path("M4 22v-5h2v3h12v-3h2v5zm0-11V2h10l6 6v3h-2V9h-5V4H6v7zm-3 4v-2h22v2zm11 2");
}

</style>
