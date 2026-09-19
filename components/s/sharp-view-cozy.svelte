<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajvpkp0ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-view-cozy" {...props}></Icon>
<style>
:global(.ajvpkp0ft) {
  fill: currentColor;
  d: path("M22 4H2v16h20zM11.25 16.75h-4v-4h4zm0-5.5h-4v-4h4zm5.5 5.5h-4v-4h4zm0-5.5h-4v-4h4z");
}

</style>
