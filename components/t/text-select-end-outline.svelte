<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf-voab1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:text-select-end-outline" {...props}></Icon>
<style>
:global(.wf-voab1s) {
  fill: currentColor;
  d: path("M11.385 5.23V4h1.23v1.23zm0 14.77v-1.23h1.23V20zM7.692 5.23V4h1.231v1.23zm0 14.77v-1.23h1.231V20zM4 5.23V4h1.23v1.23zm0 3.693v-1.23h1.23v1.23zm0 3.693v-1.231h1.23v1.23zm0 3.692v-1.231h1.23v1.23zM4 20v-1.23h1.23V20zm11 0v-1h2V5h-2V4h5v1h-2v14h2v1z");
}

</style>
