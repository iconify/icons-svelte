<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zphq_iblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-straighten" {...props}></Icon>
<style>
:global(.zphq_iblu) {
  fill: currentColor;
  d: path("M23 6H1v12h22zm-2 10H3V8h2v4h2V8h2v4h2V8h2v4h2V8h2v4h2V8h2z");
}

</style>
