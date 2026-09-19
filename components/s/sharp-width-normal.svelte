<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srxdbmbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-width-normal" {...props}></Icon>
<style>
:global(.srxdbmbht) {
  fill: currentColor;
  d: path("M22 4H2v16h20zM4 6h4v12H4zm16 12h-4V6h4z");
}

</style>
