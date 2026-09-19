<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkerpptjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-smart-display" {...props}></Icon>
<style>
:global(.wkerpptjt) {
  fill: currentColor;
  d: path("M22 4H2v16h20zM9.5 16.5v-9l7 4.5z");
}

</style>
