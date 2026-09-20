<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnn7qwwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:south-east-outline-sharp" {...props}></Icon>
<style>
:global(.vbnn7qwwz) {
  fill: currentColor;
  d: path("M9 19v-2h6.6L4 5.4L5.4 4L17 15.6V9h2v10z");
}

</style>
