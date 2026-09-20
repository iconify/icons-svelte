<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xevf-bbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-headline" {...props}></Icon>
<style>
:global(.xevf-bbet) {
  fill: currentColor;
  d: path("M4.5 14.385v-1h15v1zm0 3.769v-1h15v1zm0-7.538v-1h15v1zm0-3.77v-1h15v1z");
}

</style>
