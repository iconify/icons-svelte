<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyw1w0bzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stack-sharp" {...props}></Icon>
<style>
:global(.uyw1w0bzd) {
  fill: currentColor;
  d: path("M6 14v2H2V2h14v4h-2V4H4v10zm2 8V8h14v14z");
}

</style>
