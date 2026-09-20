<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ai8znbbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-stream" {...props}></Icon>
<style>
:global(.ai8znbbzz) {
  fill: currentColor;
  d: path("M3 19v-6h18v6zm0-8V5h18v6z");
}

</style>
