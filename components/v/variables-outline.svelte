<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp19homph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:variables-outline" {...props}></Icon>
<style>
:global(.bp19homph) {
  fill: currentColor;
  d: path("M4 16V8h16v8zm1-1h14V9H5zm0 0V9z");
}

</style>
