<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdbp_p5yp"/><path class="im-o75nsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-quickreply" {...props}></Icon>
<style>
:global(.fdbp_p5yp) {
  fill: currentColor;
  d: path("M22 2H2v20l4-4h9v-8h7z");
}

:global(.im-o75nsy) {
  fill: currentColor;
  d: path("M22.5 16h-2.2l1.7-4h-5v6h2v5z");
}

</style>
